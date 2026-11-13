---
title: Twake node documentation
description: >-
  Learn how to use the Twake node in n8n. Follow technical documentation to
  integrate Twake node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Twake node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.twake.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.twake'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.twake'
layout:
  description:
    visible: false
---

# Twake node <a href="#twake-node" id="twake-node"></a>

Use the Twake node to automate work in Twake, and integrate Twake with other applications. n8n supports sending messages with Twake.

On this page, you'll find a list of operations the Twake node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Twake credentials](../credentials/twake.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Message
    * Send a message

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Twake node documentation integration templates](https://n8n.io/integrations/twake) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
