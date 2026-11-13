---
title: SendGrid node documentation
description: >-
  Learn how to use the SendGrid node in n8n. Follow technical documentation to
  integrate SendGrid node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: SendGrid node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.sendgrid.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.sendgrid'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.sendgrid'
layout:
  description:
    visible: false
---

# SendGrid node <a href="#sendgrid-node" id="sendgrid-node"></a>

Use the SendGrid node to automate work in SendGrid, and integrate SendGrid with other applications. n8n has built-in support for a wide range of SendGrid features, including creating, updating, deleting, and getting contacts, and lists, as well as sending emails. 

On this page, you'll find a list of operations the SendGrid node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [SendGrid credentials](../credentials/sendgrid.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Contact
    * Create/update a contact
    * Delete a contact
    * Get a contact by ID
    * Get all contacts
* List
    * Create a list
    * Delete a list
    * Get a list
    * Get all lists
    * Update a list
* Mail
    * Send an email.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse SendGrid node documentation integration templates](https://n8n.io/integrations/sendgrid) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
