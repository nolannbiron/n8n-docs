---
title: APITemplate.io node documentation
description: >-
  Learn how to use the APITemplate.io node in n8n. Follow technical
  documentation to integrate APITemplate.io node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: APITemplate.io node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.apitemplateio.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.apitemplateio
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.apitemplateio
layout:
  description:
    visible: false
---

# APITemplate.io node <a href="#apitemplateio-node" id="apitemplateio-node"></a>

Use the APITemplate.io node to automate work in APITemplate.io, and integrate APITemplate.io with other applications. n8n has built-in support for a wide range of APITemplate.io features, including getting and creating accounts and PDF.

On this page, you'll find a list of operations the APITemplate.io node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [APITemplate.io credentials](../credentials/apitemplateio.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Account
    * Get
* Image
    * Create
* PDF
    * Create

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse APITemplate.io node documentation integration templates](https://n8n.io/integrations/apitemplateio) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

