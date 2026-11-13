---
title: Stripe node documentation
description: >-
  Learn how to use the Stripe node in n8n. Follow technical documentation to
  integrate Stripe node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Stripe node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.stripe.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.stripe'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.stripe'
layout:
  description:
    visible: false
---

# Stripe node <a href="#stripe-node" id="stripe-node"></a>

Use the Stripe node to automate work in Stripe, and integrate Stripe with other applications. n8n has built-in support for a wide range of Stripe features, including getting balance, creating charge and meter events, and deleting customers. 

On this page, you'll find a list of operations the Stripe node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Stripe credentials](../credentials/stripe.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Balance
    * Get a balance
* Charge
    * Create a charge
    * Get a charge
    * Get all charges
    * Update a charge
* Coupon
    * Create a coupon
    * Get all coupons
* Customer
    * Create a customer
    * Delete a customer
    * Get a customer
    * Get all customers
    * Update a customer
* Customer Card
    * Add a customer card
    * Get a customer card
    * Remove a customer card
* Meter Event
    * Create a meter event
* Source
    * Create a source
    * Delete a source
    * Get a source
* Token
    * Create a token

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Stripe node documentation integration templates](https://n8n.io/integrations/stripe) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
