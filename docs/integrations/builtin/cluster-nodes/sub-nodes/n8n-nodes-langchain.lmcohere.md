---
title: Cohere Model node documentation
contentType:
  - integration
  - reference
nodeTitle: Cohere Model node documentation
originalFilePath: integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmcohere.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmcohere
url: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmcohere
description: >-
  Learn how to use the Cohere Model node in n8n. Follow technical documentation
  to integrate Cohere Model node into your workflows.
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
  anchors:
    visible: true
---

# Cohere Model

Use the Cohere Model node to use Cohere's models.

On this page, you'll find the node parameters for the Cohere Model node, and links to more resources.

This node lacks tools support, so it won't work with the [AI Agent](../root-nodes/n8n-nodes-langchain.agent/) node. Instead, connect it with the [Basic LLM Chain](../root-nodes/n8n-nodes-langchain.chainllm.md) node.

{% hint style="info" %}
**Credentials**

Refer to the [Cohere credentials documentation](../../credentials/cohere.md) for authentication information for this node.
{% endhint %}

{% hint style="info" %}
**Parameter resolution in sub-nodes**

Sub-nodes behave differently to other nodes when processing multiple items using an expression.

Most nodes, including root nodes, take any number of items as input, process these items, and output the results. You can use expressions to refer to input items, and the node resolves the expression for each item in turn. For example, given an input of five `name` values, the expression `{{ $json.name }}` resolves to each name in turn.

In sub-nodes, the expression always resolves to the first item. For example, given an input of five `name` values, the expression `{{ $json.name }}` always resolves to the first name.
{% endhint %}

## Node Options <a href="#node-options" id="node-options"></a>

* **Maximum Number of Tokens**: Enter the maximum number of tokens used, which sets the completion length.
* **Sampling Temperature**: Use this option to control the randomness of the sampling process. A higher temperature creates more diverse sampling, but increases the risk of hallucinations.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Cohere Model node documentation integration templates](https://n8n.io/integrations/cohere-model) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [LangChain's Cohere documentation](https://docs.langchain.com/oss/javascript/integrations/llms/cohere) for more information about the service.

View n8n's [Advanced AI](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai) documentation.
