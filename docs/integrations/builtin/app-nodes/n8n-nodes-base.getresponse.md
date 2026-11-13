---
title: GetResponse node documentation
description: >-
  Learn how to use the GetResponse node in n8n. Follow technical documentation
  to integrate GetResponse node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: GetResponse node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.getresponse.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.getresponse'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.getresponse'
layout:
  description:
    visible: false
---

# GetResponse node <a href="#getresponse-node" id="getresponse-node"></a>

Use the GetResponse node to automate work in GetResponse, and integrate GetResponse with other applications. n8n has built-in support for a wide range of GetResponse features, including creating, updating, deleting, and getting contacts. 

On this page, you'll find a list of operations the GetResponse node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [GetResponse credentials](../credentials/getresponse.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Contact
    * Create a new contact
    * Delete a contact
    * Get a contact
    * Get all contacts
    * Update contact properties

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse GetResponse node documentation integration templates](https://n8n.io/integrations/getresponse) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.

