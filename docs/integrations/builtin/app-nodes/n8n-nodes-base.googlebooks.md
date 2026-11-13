---
title: Google Books node documentation
contentType:
  - integration
  - reference
nodeTitle: Google Books node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googlebooks.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlebooks
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlebooks
description: >-
  Learn how to use the Google Books node in n8n. Follow technical documentation
  to integrate Google Books node into your workflows.
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

# Google Books

Use the Google Books node to automate work in Google Books, and integrate Google Books with other applications. n8n has built-in support for a wide range of Google Books features, including retrieving a specific bookshelf resource for the specified user, adding volume to a bookshelf, and getting volume.

On this page, you'll find a list of operations the Google Books node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Google credentials](../credentials/google/) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Bookshelf
  * Retrieve a specific bookshelf resource for the specified user
  * Get all public bookshelf resource for the specified user
* Bookshelf Volume
  * Add a volume to a bookshelf
  * Clears all volumes from a bookshelf
  * Get all volumes in a specific bookshelf for the specified user
  * Moves a volume within a bookshelf
  * Removes a volume from a bookshelf
* Volume
  * Get a volume resource based on ID
  * Get all volumes filtered by query

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Google Books node documentation integration templates](https://n8n.io/integrations/google-books) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
