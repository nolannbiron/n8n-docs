---
title: Linear node documentation
contentType:
  - integration
  - reference
nodeTitle: Linear node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.linear.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.linear
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.linear
description: >-
  Learn how to use the Linear node in n8n. Follow technical documentation to
  integrate Linear node into your workflows.
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

# Linear

Use the Linear node to automate work in Linear, and integrate Linear with other applications. n8n has built-in support for a wide range of Linear features, including creating, updating, deleting, and getting issues.

On this page, you'll find a list of operations the Linear node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Linear credentials](../credentials/linear.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Comment
  * Add Comment
* Issue
  * Add Link
  * Create
  * Delete
  * Get
  * Get Many
  * Update

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Linear node documentation integration templates](https://n8n.io/integrations/linear) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
