---
title: Webex by Cisco node documentation
description: >-
  Learn how to use the Webex by Cisco node in n8n. Follow technical
  documentation to integrate Webex by Cisco node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Webex by Cisco node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.ciscowebex.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.ciscowebex'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.ciscowebex'
layout:
  description:
    visible: false
---

# Webex by Cisco node <a href="#webex-by-cisco-node" id="webex-by-cisco-node"></a>

Use the Webex by Cisco node to automate work in Webex, and integrate Webex with other applications. n8n has built-in support for a wide range of Webex features, including creating, getting, updating, and deleting meetings and messages.

On this page, you'll find a list of operations the Webex node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Webex credentials](../credentials/ciscowebex.md) for guidance on setting up authentication.
{% endhint %}
{% hint style="info" %}
**Examples and Templates**

For usage examples and templates to help you get started, take a look at n8n's [Webex integrations](https://n8n.io/integrations/webex-by-cisco/) list.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Meeting
    * Create
    * Delete
    * Get
    * Get All
    * Update
* Message
    * Create
    * Delete
    * Get
    * Get All
    * Update

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Webex by Cisco node documentation integration templates](https://n8n.io/integrations/webex-by-cisco) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

