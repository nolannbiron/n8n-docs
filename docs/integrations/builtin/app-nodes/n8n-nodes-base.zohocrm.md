---
title: Zoho CRM node documentation
description: >-
  Learn how to use the Zoho CRM node in n8n. Follow technical documentation to
  integrate Zoho CRM node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Zoho CRM node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.zohocrm.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.zohocrm'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.zohocrm'
layout:
  description:
    visible: false
---

# Zoho CRM node <a href="#zoho-crm-node" id="zoho-crm-node"></a>

Use the Zoho CRM node to automate work in Zoho CRM, and integrate Zoho CRM with other applications. n8n has built-in support for a wide range of Zoho CRM features, including creating and deleting accounts, contacts, and deals. 

On this page, you'll find a list of operations the Zoho CRM node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Zoho CRM credentials](../credentials/zoho.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Account
    * Create an account
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete an account
    * Get an account
    * Get all accounts
    * Update an account
* Contact
    * Create a contact
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a contact
    * Get a contact
    * Get all contacts
    * Update a contact
* Deal
    * Create a deal
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a contact
    * Get a contact
    * Get all contacts
    * Update a contact
* Invoice
    * Create an invoice
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete an invoice
    * Get an invoice
    * Get all invoices
    * Update an invoice
* Lead
    * Create a lead
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a lead
    * Get a lead
    * Get all leads
    * Get lead fields
    * Update a lead
* Product
    * Create a product
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a product
    * Get a product
    * Get all products
    * Update a product
* Purchase Order
    * Create a purchase order
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a purchase order
    * Get a purchase order
    * Get all purchase orders
    * Update a purchase order
* Quote
    * Create a quote
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a quote
    * Get a quote
    * Get all quotes
    * Update a quote
* Sales Order
    * Create a sales order
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a sales order
    * Get a sales order
    * Get all sales orders
    * Update a sales order
* Vendor
    * Create a vendor
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a vendor
    * Get a vendor
    * Get all vendors
    * Update a vendor

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Zoho CRM node documentation integration templates](https://n8n.io/integrations/zoho-crm) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
