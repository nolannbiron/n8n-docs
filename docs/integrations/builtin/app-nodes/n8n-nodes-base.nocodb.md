---
title: NocoDB node documentation
description: >-
  Learn how to use the NocoDB node in n8n. Follow technical documentation to
  integrate NocoDB node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: NocoDB node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.nocodb.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.nocodb'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.nocodb'
layout:
  description:
    visible: false
---

# NocoDB node <a href="#nocodb-node" id="nocodb-node"></a>

Use the NocoDB node to automate work in NocoDB, and integrate NocoDB with other applications. n8n has built-in support for a wide range of NocoDB features, including creating, updating, deleting, and retrieving rows. 

On this page, you'll find a list of operations the NocoDB node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [NocoDB credentials](../credentials/nocodb.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Row
    * Create
    * Delete
    * Get
    * Get Many
    * Update a row

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse NocoDB node documentation integration templates](https://n8n.io/integrations/nocodb) or [search all templates](https://n8n.io/workflows/)

## Relates resources <a href="#relates-resources" id="relates-resources"></a>

Refer to [NocoDB's documentation](https://docs.nocodb.com/) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
