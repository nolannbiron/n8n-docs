---
title: Magento 2 node documentation
description: >-
  Learn how to use the Magento 2 node in n8n. Follow technical documentation to
  integrate Magento 2 node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Magento 2 node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.magento2.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.magento2'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.magento2'
layout:
  description:
    visible: false
---

# Magento 2 node <a href="#magento-2-node" id="magento-2-node"></a>

Use the Magento 2 node to automate work in Magento 2, and integrate Magento 2 with other applications. n8n has built-in support for a wide range of Magento 2 features, including creating, updating, deleting, and getting customers, invoices, orders, and projects. 

On this page, you'll find a list of operations the Magento 2 node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Magento 2 credentials](../credentials/magento2.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Customer
    * Create a new customer
    * Delete a customer
    * Get a customer
    * Get all customers
    * Update a customer
* Invoice
    * Create an invoice
* Order
    * Cancel an order
    * Get an order
    * Get all orders
    * Ship an order
* Product
    * Create a product
    * Delete a product
    * Get a product
    * Get all products
    * Update a product

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Magento 2 node documentation integration templates](https://n8n.io/integrations/magento-2) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
