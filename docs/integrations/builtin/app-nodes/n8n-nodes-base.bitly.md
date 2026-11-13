---
title: Bitly node documentation
description: >-
  Learn how to use the Bitly node in n8n. Follow technical documentation to
  integrate Bitly node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Bitly node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.bitly.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.bitly'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.bitly'
layout:
  description:
    visible: false
---

# Bitly node <a href="#bitly-node" id="bitly-node"></a>

Use the Bitly node to automate work in Bitly, and integrate Bitly with other applications. n8n has built-in support for a wide range of Bitly features, including creating, getting, and updating links.

On this page, you'll find a list of operations the Bitly node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Bitly credentials](../credentials/bitly.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Link
    * Create a link
    * Get a link
    * Update a link

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Bitly node documentation integration templates](https://n8n.io/integrations/bitly) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

