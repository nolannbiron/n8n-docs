---
title: HubSpot node documentation
contentType:
  - integration
  - reference
priority: medium
nodeTitle: HubSpot node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.hubspot.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.hubspot
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.hubspot
description: >-
  Learn how to use the HubSpot node in n8n. Follow technical documentation to
  integrate HubSpot node into your workflows.
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

# HubSpot

Use the HubSpot node to automate work in HubSpot, and integrate HubSpot with other applications. n8n has built-in support for a wide range of HubSpot features, including creating, updating, deleting, and getting contacts, deals, lists, engagements and companies.

On this page, you'll find a list of operations the HubSpot node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [HubSpot credentials](../credentials/hubspot.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Contact
  * Create/Update a contact
  * Delete a contact
  * Get a contact
  * Get all contacts
  * Get recently created/updated contacts
  * Search contacts
* Contact List
  * Add contact to a list
  * Remove a contact from a list
* Company
  * Create a company
  * Delete a company
  * Get a company
  * Get all companies
  * Get recently created companies
  * Get recently modified companies
  * Search companies by domain
  * Update a company
* Deal
  * Create a deal
  * Delete a deal
  * Get a deal
  * Get all deals
  * Get recently created deals
  * Get recently modified deals
  * Search deals
  * Update a deal
* Engagement
  * Create an engagement
  * Delete an engagement
  * Get an engagement
  * Get all engagements
* Form
  * Get all fields from a form
  * Submit data to a form
* Ticket
  * Create a ticket
  * Delete a ticket
  * Get a ticket
  * Get all tickets
  * Update a ticket

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse HubSpot node documentation integration templates](https://n8n.io/integrations/hubspot) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
