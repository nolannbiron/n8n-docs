---
title: Raindrop node documentation
contentType:
  - integration
  - reference
nodeTitle: Raindrop node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.raindrop.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.raindrop
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.raindrop
description: >-
  Learn how to use the Raindrop node in n8n. Follow technical documentation to
  integrate Raindrop node into your workflows.
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

# Raindrop

Use the Raindrop node to automate work in Raindrop, and integrate Raindrop with other applications. n8n has built-in support for a wide range of Raindrop features, including getting users, deleting tags, and creating, updating, deleting and getting collections and bookmarks.

On this page, you'll find a list of operations the Raindrop node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Raindrop credentials](../credentials/raindrop.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Bookmark
  * Create
  * Delete
  * Get
  * Get All
  * Update
* Collection
  * Create
  * Delete
  * Get
  * Get All
  * Update
* Tag
  * Delete
  * Get All
* User
  * Get

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Raindrop node documentation integration templates](https://n8n.io/integrations/raindrop) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
