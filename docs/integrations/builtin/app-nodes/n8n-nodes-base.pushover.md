---
title: Pushover node documentation
description: >-
  Learn how to use the Pushover node in n8n. Follow technical documentation to
  integrate Pushover node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Pushover node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.pushover.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.pushover'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.pushover'
layout:
  description:
    visible: false
---

# Pushover node <a href="#pushover-node" id="pushover-node"></a>

Use the Pushover node to automate work in Pushover, and integrate Pushover with other applications. n8n supports sending push notifications with Pushover.

On this page, you'll find a list of operations the Pushover node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Pushover credentials](../credentials/pushover.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Message
    * Push

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Pushover node documentation integration templates](https://n8n.io/integrations/pushover) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
