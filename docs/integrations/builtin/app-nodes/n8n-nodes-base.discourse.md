---
title: Discourse node documentation
description: >-
  Learn how to use the Discourse node in n8n. Follow technical documentation to
  integrate Discourse node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Discourse node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.discourse.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.discourse'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.discourse'
layout:
  description:
    visible: false
---

# Discourse node <a href="#discourse-node" id="discourse-node"></a>

Use the Discourse node to automate work in Discourse, and integrate Discourse with other applications. n8n has built-in support for a wide range of Discourse features, including creating, getting, updating, and removing categories, groups, posts, and users.

On this page, you'll find a list of operations the Discourse node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Discourse credentials](../credentials/discourse.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Category
    * Create a category
    * Get all categories
    * Update a category
* Group
    * Create a group
    * Get a group
    * Get all groups
    * Update a group
* Post
    * Create a post
    * Get a post
    * Get all posts
    * Update a post
* User
    * Create a user
    * Get a user
    * Get all users
* User Group
    * Create a user to group
    * Remove user from group

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Discourse node documentation integration templates](https://n8n.io/integrations/discourse) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

