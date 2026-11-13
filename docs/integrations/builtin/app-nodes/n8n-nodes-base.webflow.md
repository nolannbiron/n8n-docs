---
title: Webflow node documentation
description: >-
  Learn how to use the Webflow node in n8n. Follow technical documentation to
  integrate Webflow node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Webflow node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.webflow.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.webflow'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.webflow'
layout:
  description:
    visible: false
---

# Webflow node <a href="#webflow-node" id="webflow-node"></a>

Use the Webflow node to automate work in Webflow, and integrate Webflow with other applications. n8n has built-in support for a wide range of Webflow features, including creating, updating, deleting, and getting items. 

On this page, you'll find a list of operations the Webflow node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Webflow credentials](../credentials/webflow.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Item
    * Create
    * Delete
    * Get
    * Get All
    * Update

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Webflow node documentation integration templates](https://n8n.io/integrations/webflow) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
