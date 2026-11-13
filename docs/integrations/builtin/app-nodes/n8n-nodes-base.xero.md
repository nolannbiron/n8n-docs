---
title: Xero node documentation
description: >-
  Learn how to use the Xero node in n8n. Follow technical documentation to
  integrate Xero node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Xero node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.xero.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.xero'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.xero'
layout:
  description:
    visible: false
---

# Xero node <a href="#xero-node" id="xero-node"></a>

Use the Xero node to automate work in Xero, and integrate Xero with other applications. n8n has built-in support for a wide range of Xero features, including creating, updating, and getting contacts and invoices. 

On this page, you'll find a list of operations the Xero node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Xero credentials](../credentials/xero.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Contact
    * Create a contact
    * Get a contact
    * Get all contacts
    * Update a contact
* Invoice
    * Create a invoice
    * Get a invoice
    * Get all invoices
    * Update a invoice

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Xero node documentation integration templates](https://n8n.io/integrations/xero) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Xero's API documentation](https://developer.xero.com/documentation/api/accounting/overview) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
