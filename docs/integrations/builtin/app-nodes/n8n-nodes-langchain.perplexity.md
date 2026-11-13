---
title: Perplexity node documentation
contentType:
  - integration
  - reference
nodeTitle: Perplexity node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-langchain.perplexity.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-langchain.perplexity
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-langchain.perplexity
description: >-
  Learn how to use the Perplexity node in n8n. Follow technical documentation to
  integrate Perplexity node into your workflows.
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

# Perplexity

Use the Perplexity node to automate work in Perplexity and integrate Perplexity with other applications. n8n has built-in support for messaging a model.

On this page, you'll find a list of operations the Perplexity node supports, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [Perplexity credentials documentation](../credentials/perplexity.md) for authentication information for this node.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* **Message a Model**: Create one or more completions for a given text.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Perplexity node documentation integration templates](https://n8n.io/integrations/perplexity) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Perplexity's documentation](https://docs.perplexity.ai/home) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
