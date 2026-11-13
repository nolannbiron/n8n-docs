---
title: Google Contacts node documentation
contentType:
  - integration
  - reference
nodeTitle: Google Contacts node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googlecontacts.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlecontacts
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlecontacts
description: >-
  Learn how to use the Google Contacts node in n8n. Follow technical
  documentation to integrate Google Contacts node into your workflows.
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

# Google Contacts

Use the Google Contacts node to automate work in Google Contacts, and integrate Google Contacts with other applications. n8n has built-in support for a wide range of Google Contacts features, including creating, updating, retrieving, deleting, and getting contacts.

On this page, you'll find a list of operations the Google Contacts node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Google Contacts credentials](../credentials/google/) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Contact
  * Create a contact
  * Delete a contact
  * Get a contact
  * Retrieve all contacts
  * Update a contact

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Google Contacts node documentation integration templates](https://n8n.io/integrations/google-contacts) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
