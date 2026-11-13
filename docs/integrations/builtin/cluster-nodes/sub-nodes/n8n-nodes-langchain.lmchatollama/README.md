---
title: Ollama Chat Model node documentation
description: >-
  Learn how to use the Ollama Chat Model node in n8n. Follow technical
  documentation to integrate Ollama Chat Model node into your workflows.
contentType:
  - integration
  - reference
priority: high
nodeTitle: n8n-nodes-langchain.lmchatollama
originalFilePath: >-
  integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmchatollama/index.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmchatollama
url: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmchatollama
layout:
  description:
    visible: false
---

# Ollama Chat Model node <a href="#ollama-chat-model-node" id="ollama-chat-model-node"></a>

The Ollama Chat Model node allows you use local Llama 2 models with conversational agents[^1].

On this page, you'll find the node parameters for the Ollama Chat Model node, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [Ollama credentials documentation](../../../credentials/ollama.md) for authentication information for this node.
{% endhint %}

{% hint style="info" %}
**Parameter resolution in sub-nodes**

Sub-nodes behave differently to other nodes when processing multiple items using an expression.

Most nodes, including root nodes, take any number of items as input, process these items, and output the results. You can use expressions to refer to input items, and the node resolves the expression for each item in turn. For example, given an input of five `name` values, the expression `{{ $json.name }}` resolves to each name in turn.

In sub-nodes, the expression always resolves to the first item. For example, given an input of five `name` values, the expression `{{ $json.name }}` always resolves to the first name.
{% endhint %}

## Node parameters <a href="#node-parameters" id="node-parameters"></a>

* **Model**: Select the model that generates the completion. Choose from:
	* **Llama2**
	* **Llama2 13B**
	* **Llama2 70B**
	* **Llama2 Uncensored**

Refer to the Ollama [Models Library documentation](https://ollama.com/library) for more information about available models.

## Node options <a href="#node-options" id="node-options"></a>

* **Sampling Temperature**: Use this option to control the randomness of the sampling process. A higher temperature creates more diverse sampling, but increases the risk of hallucinations.
* **Top K**: Enter the number of token choices the model uses to generate the next token.
* **Top P**: Use this option to set the probability the completion should use. Use a lower value to ignore less probable options. 

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse n8n-nodes-langchain.lmchatollama integration templates](https://n8n.io/integrations/ollama-chat-model) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [LangChain's Ollama Chat Model documentation](https://docs.langchain.com/oss/javascript/integrations/chat/ollama) for more information about the service.

View n8n's [Advanced AI](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai) documentation.

## Common issues <a href="#common-issues" id="common-issues"></a>

For common questions or issues and suggested solutions, refer to [Common issues](common-issues.md).



## Self-hosted AI Starter Kit <a href="#self-hosted-ai-starter-kit" id="self-hosted-ai-starter-kit"></a>

New to working with AI and using self-hosted n8n? Try n8n's [self-hosted AI Starter Kit](https://app.gitbook.com/s/jm0ZYRpZIPWge2ZSiDYO/host-n8n/deploy-with-the-ai-starter-kit) to get started with a proof-of-concept or demo playground using Ollama, Qdrant, and PostgreSQL.

[^1]: AI agents are artificial intelligence systems capable of responding to requests, making decisions, and performing real-world tasks for users. They use large language models (LLMs) to interpret user input and make decisions about how to best process requests using the information and resources they have available.
