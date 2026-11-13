---
title: Ghost node documentation
description: >-
  Learn how to use the Ghost node in n8n. Follow technical documentation to
  integrate Ghost node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Ghost node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.ghost.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.ghost'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.ghost'
layout:
  description:
    visible: false
---

# Ghost node <a href="#ghost-node" id="ghost-node"></a>

Use the Ghost node to automate work in Ghost, and integrate Ghost with other applications. n8n has built-in support for a wide range of Ghost features, including creating, updating, deleting, and getting posts for the Admin and content API. 

On this page, you'll find a list of operations the Ghost node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Ghost credentials](../credentials/ghost.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

### Admin API <a href="#admin-api" id="admin-api"></a>

* **Post**
    * Create a post
    * Delete a post
    * Get a post
    * Get all posts
    * Update a post


### Content API <a href="#content-api" id="content-api"></a>

* **Post**
    * Get a post
    * Get all posts

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Ghost node documentation integration templates](https://n8n.io/integrations/ghost) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.

