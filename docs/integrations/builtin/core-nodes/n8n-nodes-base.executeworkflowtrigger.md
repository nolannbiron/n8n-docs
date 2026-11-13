---
title: Execute Sub-workflow Trigger node documentation
description: >-
  Learn how to use the Execute Sub-workflow Trigger node in n8n. Follow
  technical documentation to integrate Execute Sub-workflow Trigger node into
  your workflows.
contentType:
  - integration
  - reference
priority: high
nodeTitle: Execute Sub-workflow Trigger node documentation
originalFilePath: integrations/builtin/core-nodes/n8n-nodes-base.executeworkflowtrigger.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.executeworkflowtrigger
url: >-
  https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.executeworkflowtrigger
layout:
  description:
    visible: false
---

# Execute Sub-workflow Trigger node <a href="#execute-sub-workflow-trigger-node" id="execute-sub-workflow-trigger-node"></a>

Use this node to start a workflow in response to another workflow. It should be the first node in the workflow.

n8n allows you to call workflows from other workflows. This is useful if you want to:

* Reuse a workflow: for example, you could have multiple workflows pulling and processing data from different sources, then have all those workflows call a single workflow that generates a report.
* Break large workflows into smaller components.

## Usage <a href="#usage" id="usage"></a>

This node runs in response to a call from the [Execute Sub-workflow](n8n-nodes-base.executeworkflow.md) or [Call n8n Workflow Tool](../cluster-nodes/sub-nodes/n8n-nodes-langchain.toolworkflow.md) nodes.

### Create the sub-workflow <a href="#create-the-sub-workflow" id="create-the-sub-workflow"></a>


1. Create a new workflow.<br>

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Create sub-workflows from existing workflows</strong></p><p>You can optionally create a sub-workflow directly from an existing parent workflow using the <a href="https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.executeworkflow">Execute Sub-workflow</a> node. In the node, select the <strong>Database</strong> and <strong>From list</strong> options and select <strong>Create a sub-workflow</strong> in the list.</p><p>You can also extract selected nodes directly using <a href="https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/flow-logic/convert-to-sub-workflows">Sub-workflow conversion</a> in the context menu.</p></div>

1. **Optional**: configure which workflows can call the sub-workflow:
	1. Select the **Options** <img src="../../assets/three-dot-options-menu.png" alt="Options menu" data-size="line"> menu > **Settings**. n8n opens the **Workflow settings** modal.
	1. Change the **This workflow can be called by** setting.	Refer to [Workflow settings](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/manage-workflows/configure-workflow-settings) for more information on configuring your workflows.
1. Add the **Execute Sub-workflow** trigger node (if you are searching under trigger nodes, this is also titled **When Executed by Another Workflow**).
1. Set the **Input data mode** to choose how you will define the sub-workflow's input data:
	* **Define using fields below**: Choose this mode to define individual input names and data types that the calling workflow needs to provide. The [Execute Sub-workflow node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.executeworkflow) or [Call n8n Workflow Tool node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.toolworkflow) in the calling workflow will automatically pull in the fields defined here.
	* **Define using JSON example**: Choose this mode to provide an example JSON object that demonstrates the expected input items and their types.
	* **Accept all data**: Choose this mode to accept all data unconditionally. The sub-workflow won't define any required input items. This sub-workflow must handle any input inconsistencies or missing values.
1. Add other nodes as needed to build your sub-workflow functionality.
1. Save the sub-workflow.

{% hint style="info" %}
**Sub-workflow mustn't contain errors**

If there are errors in the sub-workflow, the parent workflow can't trigger it.
{% endhint %}
{% hint style="info" %}
**Load data into sub-workflow before building**

This requires the ability to [load data from previous executions](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/understand-workflows/understand-executions/debug-executions), which is available on n8n Cloud and registered Community plans.

If you want to load data into your sub-workflow to use while building it:

1. Create the sub-workflow and add the **Execute Sub-workflow Trigger**. 
1. Set the node's **Input data mode** to **Accept all data** or define the input items using fields or JSON if they're already known.
1. In the sub-workflow [settings](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/manage-workflows/configure-workflow-settings), set **Save successful production executions** to **Save**. 
1. Skip ahead to setting up the parent workflow, and run it.
1. Follow the steps to [load data from previous executions](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/understand-workflows/understand-executions/debug-executions).
1. Adjust the **Input data mode** to match the input sent by the parent workflow if necessary.

You can now pin example data in the trigger node, enabling you to work with real data while configuring the rest of the workflow.
{% endhint %}


### Call the sub-workflow <a href="#call-the-sub-workflow" id="call-the-sub-workflow"></a>

1. Open the workflow where you want to call the sub-workflow.
1. Add the **Execute Sub-workflow** node.
1. In the **Execute Sub-workflow** node, set the sub-workflow you want to call. You can choose to call the workflow by ID, load a workflow from a local file, add workflow JSON as a parameter in the node, or target a workflow by URL.<br>

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Find your workflow ID</strong></p><p>Your sub-workflow's ID is the alphanumeric string at the end of its URL.</p></div>

1. Fill in the required input items defined by the sub-workflow.
1. Save your workflow.

When your workflow executes, it will send data to the sub-workflow, and run it.

You can follow the execution flow from the parent workflow to the sub-workflow by opening the Execute Sub-workflow node and selecting the **View sub-execution** link. Likewise, the sub-workflow's execution contains a link back to the parent workflow's execution to navigate in the other direction.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Execute Sub-workflow Trigger node documentation integration templates](https://n8n.io/integrations/execute-workflow-trigger) or [search all templates](https://n8n.io/workflows/)

## How data passes between workflows <a href="#how-data-passes-between-workflows" id="how-data-passes-between-workflows"></a>

As an example, imagine you have an Execute Sub-workflow node in **Workflow A**. The Execute Sub-workflow node calls another workflow called **Workflow B**:

1. The Execute Sub-workflow node passes the data to the Execute Sub-workflow Trigger node (titled "When executed by another node" in the canvas) of **Workflow B**.
2. The last node of **Workflow B** sends the data back to the Execute Sub-workflow node in **Workflow A**.
