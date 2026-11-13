---
title: Embeddings HuggingFace Inference node documentation
description: >-
  Learn how to use the Embeddings HuggingFace Inference node in n8n. Follow
  technical documentation to integrate Embeddings HuggingFace Inference node
  into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Embeddings HuggingFace Inference node documentation
originalFilePath: >-
  integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.embeddingshuggingfaceinference.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.embeddingshuggingfaceinference
url: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.embeddingshuggingfaceinference
layout:
  description:
    visible: false
---

# Embeddings HuggingFace Inference node <a href="#embeddings-huggingface-inference-node" id="embeddings-huggingface-inference-node"></a>

Use the Embeddings HuggingFace Inference node to generate embeddings[^1] for a given text.

On this page, you'll find the node parameters for the Embeddings HuggingFace Inference, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [Hugging Face credentials documentation](../../credentials/huggingface.md) for authentication information for this node.
{% endhint %}

{% hint style="info" %}
**Parameter resolution in sub-nodes**

Sub-nodes behave differently to other nodes when processing multiple items using an expression.

Most nodes, including root nodes, take any number of items as input, process these items, and output the results. You can use expressions to refer to input items, and the node resolves the expression for each item in turn. For example, given an input of five `name` values, the expression `{{ $json.name }}` resolves to each name in turn.

In sub-nodes, the expression always resolves to the first item. For example, given an input of five `name` values, the expression `{{ $json.name }}` always resolves to the first name.
{% endhint %}

## Node parameters <a href="#node-parameters" id="node-parameters"></a>

* **Model**: Select the model to use to generate the embedding.

Refer to the [Hugging Face models documentation](https://huggingface.co/models?other=embeddings) for available models.

## Node options <a href="#node-options" id="node-options"></a>

* **Custom Inference Endpoint**: Enter the URL of your deployed model, hosted by HuggingFace. If you set this, n8n ignores the **Model Name**.

Refer to [HuggingFace's guide to inference](https://huggingface.co/inference-endpoints) for more information.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Embeddings HuggingFace Inference node documentation integration templates](https://n8n.io/integrations/embeddings-hugging-face-inference) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

View n8n's [Advanced AI](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai) documentation.

[^1]: Embeddings are numerical representations of data using vectors. They're used by AI to interpret complex data and relationships by mapping values across many dimensions. Vector databases, or vector stores, are databases designed to store and access embeddings.
