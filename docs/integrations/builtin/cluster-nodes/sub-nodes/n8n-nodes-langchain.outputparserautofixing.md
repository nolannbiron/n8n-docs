---
title: Auto-fixing Output Parser node documentation
description: >-
  Learn how to use the Auto-fixing Output Parser node in n8n. Follow technical
  documentation to integrate Auto-fixing Output Parser node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Auto-fixing Output Parser node documentation
originalFilePath: >-
  integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.outputparserautofixing.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.outputparserautofixing
url: >-
  https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.outputparserautofixing
layout:
  description:
    visible: false
---

# Auto-fixing Output Parser node <a href="#auto-fixing-output-parser-node" id="auto-fixing-output-parser-node"></a>

The Auto-fixing Output Parser node wraps another output parser. If the first one fails, it calls out to another LLM to fix any errors.

{% hint style="info" %}
**Parameter resolution in sub-nodes**

Sub-nodes behave differently to other nodes when processing multiple items using an expression.

Most nodes, including root nodes, take any number of items as input, process these items, and output the results. You can use expressions to refer to input items, and the node resolves the expression for each item in turn. For example, given an input of five `name` values, the expression `{{ $json.name }}` resolves to each name in turn.

In sub-nodes, the expression always resolves to the first item. For example, given an input of five `name` values, the expression `{{ $json.name }}` always resolves to the first name.
{% endhint %}

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Auto-fixing Output Parser node documentation integration templates](https://n8n.io/integrations/auto-fixing-output-parser) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [LangChain's structured output documentation](https://docs.langchain.com/oss/javascript/langchain/structured-output) for more information about the service.

View n8n's [Advanced AI](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai) documentation.

