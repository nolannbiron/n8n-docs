---
title: ERPNext node documentation
description: >-
  Learn how to use the ERPNext node in n8n. Follow technical documentation to
  integrate ERPNext node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: ERPNext node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.erpnext.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.erpnext'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.erpnext'
layout:
  description:
    visible: false
---

# ERPNext node <a href="#erpnext-node" id="erpnext-node"></a>

Use the ERPNext node to automate work in ERPNext, and integrate ERPNext with other applications. n8n has built-in support for a wide range of ERPNext features, including creating, updating, retrieving, and deleting documents. 

On this page, you'll find a list of operations the ERPNext node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [ERPNext credentials](../credentials/erpnext.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

**Document**
- Create a document
- Delete a document
- Retrieve a document
- Retrieve all documents
- Update a document

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse ERPNext node documentation integration templates](https://n8n.io/integrations/erpnext) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

