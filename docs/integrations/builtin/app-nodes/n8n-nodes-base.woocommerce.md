---
title: WooCommerce node documentation
description: >-
  Learn how to use the WooCommerce node in n8n. Follow technical documentation
  to integrate WooCommerce node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: WooCommerce node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.woocommerce.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.woocommerce'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.woocommerce'
layout:
  description:
    visible: false
---

# WooCommerce node <a href="#woocommerce-node" id="woocommerce-node"></a>

Use the WooCommerce node to automate work in WooCommerce, and integrate WooCommerce with other applications. n8n has built-in support for a wide range of WooCommerce features, including creating and deleting customers, orders, and products. 

On this page, you'll find a list of operations the WooCommerce node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [WooCommerce credentials](../credentials/woocommerce.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Customer
    * Create a customer
    * Delete a customer
    * Retrieve a customer
    * Retrieve all customers
    * Update a customer
* Order
    * Create a order
    * Delete a order
    * Get a order
    * Get all orders
    * Update an order
* Product
    * Create a product
    * Delete a product
    * Get a product
    * Get all products
    * Update a product

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse WooCommerce node documentation integration templates](https://n8n.io/integrations/woocommerce) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.

