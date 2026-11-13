---
title: Keap node documentation
contentType:
  - integration
  - reference
nodeTitle: Keap node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.keap.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.keap
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.keap
description: >-
  Learn how to use the Keap node in n8n. Follow technical documentation to
  integrate Keap node into your workflows.
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

# Keap

Use the Keap node to automate work in Keap, and integrate Keap with other applications. n8n has built-in support for a wide range of Keap features, including creating, updating, deleting, and getting companies, products, ecommerce orders, emails, and files.

On this page, you'll find a list of operations the Keap node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Keap credentials](../credentials/keap.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Company
  * Create a company
  * Retrieve all companies
* Contact
  * Create/update a contact
  * Delete an contact
  * Retrieve an contact
  * Retrieve all contacts
* Contact Note
  * Create a note
  * Delete a note
  * Get a notes
  * Retrieve all notes
  * Update a note
* Contact Tag
  * Add a list of tags to a contact
  * Delete a contact's tag
  * Retrieve all contact's tags
* Ecommerce Order
  * Create an ecommerce order
  * Get an ecommerce order
  * Delete an ecommerce order
  * Retrieve all ecommerce orders
* Ecommerce Product
  * Create an ecommerce product
  * Delete an ecommerce product
  * Get an ecommerce product
  * Retrieve all ecommerce product
* Email
  * Create a record of an email sent to a contact
  * Retrieve all sent emails
  * Send Email
* File
  * Delete a file
  * Retrieve all files
  * Upload a file

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Keap node documentation integration templates](https://n8n.io/integrations/keap) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
