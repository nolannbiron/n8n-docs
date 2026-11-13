---
title: MultiQuery Retriever node documentation
description: >-
  Learn how to use the MultiQuery Retriever node in n8n. Follow technical
  documentation to integrate MultiQuery Retriever node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: MultiQuery Retriever node documentation
originalFilePath: >-
  integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.retrievermultiquery.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.retrievermultiquery
url: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.retrievermultiquery
layout:
  description:
    visible: false
---

# MultiQuery Retriever node <a href="#multiquery-retriever-node" id="multiquery-retriever-node"></a>

The MultiQuery Retriever node automates the process of prompt tuning by using an LLM to generate multiple queries from different perspectives for a given user input query.

On this page, you'll find the node parameters for the MultiQuery Retriever node, and links to more resources.

{% hint style="info" %}
**Parameter resolution in sub-nodes**

Sub-nodes behave differently to other nodes when processing multiple items using an expression.

Most nodes, including root nodes, take any number of items as input, process these items, and output the results. You can use expressions to refer to input items, and the node resolves the expression for each item in turn. For example, given an input of five `name` values, the expression `{{ $json.name }}` resolves to each name in turn.

In sub-nodes, the expression always resolves to the first item. For example, given an input of five `name` values, the expression `{{ $json.name }}` always resolves to the first name.
{% endhint %}

## Node options <a href="#node-options" id="node-options"></a>

* **Query Count**: Enter how many different versions of the query to generate.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse MultiQuery Retriever node documentation integration templates](https://n8n.io/integrations/multiquery-retriever) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [LangChain's retriever documentation](https://docs.langchain.com/oss/javascript/integrations/retrievers) for more information about the service.

View n8n's [Advanced AI](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai) documentation.

