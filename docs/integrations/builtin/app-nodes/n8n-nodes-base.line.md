---
title: Line node documentation
description: >-
  Learn how to use the Line node in n8n. Follow technical documentation to
  integrate Line node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Line node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.line.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.line'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.line'
layout:
  description:
    visible: false
tags:
  - tag: deprecated
    primary: true
---

# Line node <a href="#line-node" id="line-node"></a>


{% hint style="warning" %}
**Feature availability**

The Line node is deprecated from n8n 1.64.0. LINE Notify ends its own service on April 1, 2025, after which the node stops working. View LINE Notify's [end of service announcement](https://notify-bot.line.me/closing-announce) for more information.
{% endhint %}


Use the Line node to automate work in Line, and integrate Line with other applications. n8n has built-in support for a wide range of Line features, including sending notifications. 

On this page, you'll find a list of operations the Line node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Line credentials](../credentials/line.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Notification
    * Sends notifications to users or groups

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Line node documentation integration templates](https://n8n.io/integrations/line) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
