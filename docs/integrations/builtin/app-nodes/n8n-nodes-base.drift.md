---
title: Drift node documentation
description: >-
  Learn how to use the Drift node in n8n. Follow technical documentation to
  integrate Drift node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Drift node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.drift.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.drift'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.drift'
layout:
  description:
    visible: false
---

# Drift node <a href="#drift-node" id="drift-node"></a>

Use the Drift node to automate work in Drift, and integrate Drift with other applications. n8n has built-in support for a wide range of Drift features, including creating, updating, deleting, and getting contacts. 

On this page, you'll find a list of operations the Drift node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Drift credentials](../credentials/drift.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Contact
    * Create a contact
    * Get custom attributes
    * Delete a contact
    * Get a contact
    * Update a contact

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Drift node documentation integration templates](https://n8n.io/integrations/drift) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

