---
title: OpenAI Functions Agent node documentation
contentType:
  - integration
  - reference
priority: critical
nodeTitle: OpenAI Functions Agent node documentation
originalFilePath: >-
  integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.agent/openai-functions-agent.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.agent/openai-functions-agent
url: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.agent/openai-functions-agent
description: >-
  Learn how to use the OpenAI Functions Agent of the AI Agent node in n8n.
  Follow technical documentation to integrate the OpenAI Functions Agent into
  your workflows.
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
tags:
  - tag: deprecated
    primary: true
---

# OpenAI Functions Agent

{% hint style="warning" %}
**Feature availability**

The OpenAI Functions Agent is deprecated from n8n 1.82.0. New or updated AI Agent nodes use the [Tools Agent](tools-agent.md) instead. Only workflows still using node version 1 of the AI Agent node can select the OpenAI Functions Agent.

Node version 1 of the AI Agent node is removed from n8n 3.0, so the OpenAI Functions Agent stops working for all workflows. See [n8n 3.0 breaking changes](https://app.gitbook.com/s/hhM8Cox90Piiv0u0EgHM/v30-breaking-changes) for details.
{% endhint %}

Use the OpenAI Functions Agent node to use an [OpenAI functions model](https://platform.openai.com/docs/guides/function-calling). These are models that detect when a function should be called and respond with the inputs that should be passed to the function.

Refer to [AI Agent](./README.md) for more information on the AI Agent node itself.

You can use this agent with the [Chat Trigger](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-langchain.chattrigger) node. Attach a memory sub-node so that users can have an ongoing conversation with multiple queries. Memory doesn't persist between sessions.

{% hint style="info" %}
**OpenAI Chat Model required**

You must use the [OpenAI Chat Model](../../sub-nodes/n8n-nodes-langchain.lmchatopenai/README.md) with this agent.
{% endhint %}

## Node parameters <a href="#node-parameters" id="node-parameters"></a>

Configure the OpenAI Functions Agent using the following parameters.

### Prompt <a href="#prompt" id="prompt"></a>

Select how you want the node to construct the prompt (also known as the user's query or input from the chat).

Choose from:

* **Take from previous node automatically**: If you select this option, the node expects an input from a previous node called `chatInput`.
* **Define below**: If you select this option, provide either static text or an expression for dynamic content to serve as the prompt in the **Prompt (User Message)** field.

### Require Specific Output Format <a href="#require-specific-output-format" id="require-specific-output-format"></a>

This parameter controls whether you want the node to require a specific output format. When turned on, n8n prompts you to connect one of these output parsers to the node:

* [Auto-fixing Output Parser](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.outputparserautofixing)
* [Item List Output Parser](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.outputparseritemlist)
* [Structured Output Parser](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.outputparserstructured)

## Node options <a href="#node-options" id="node-options"></a>

Refine the OpenAI Functions Agent node's behavior using these options:

### System Message <a href="#system-message" id="system-message"></a>

If you'd like to send a message to the agent before the conversation starts, enter the message you'd like to send.

Use this option to guide the agent's decision-making.

### Max Iterations <a href="#max-iterations" id="max-iterations"></a>

Enter the number of times the model should run to try and generate a good answer from the user's prompt.

Defaults to `10`.

### Return Intermediate Steps <a href="#return-intermediate-steps" id="return-intermediate-steps"></a>

Select whether to include intermediate steps the agent took in the final output (turned on) or not (turned off).

This could be useful for further refining the agent's behavior based on the steps it took.

### Tracing Metadata <a href="#tracing-metadata" id="tracing-metadata"></a>

Add custom key-value metadata to tracing events for this agent. This is useful for filtering and debugging runs in tracing tools like [LangSmith](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/langchain-in-n8n#use-langsmith-with-a-self-hosted-n8n-instance).

Entries with empty keys or values are ignored.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

Refer to the main AI Agent node's [Templates and examples](./README.md#templates-and-examples) section.

## Common issues <a href="#common-issues" id="common-issues"></a>

For common questions or issues and suggested solutions, refer to [Common issues](common-issues.md).
