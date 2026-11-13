---
title: Metabase node documentation
description: >-
  Learn how to use the Metabase node in n8n. Follow technical documentation to
  integrate Metabase node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Metabase node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.metabase.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.metabase'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.metabase'
layout:
  description:
    visible: false
---

# Metabase node <a href="#metabase-node" id="metabase-node"></a>

Use the Metabase node to automate work in Metabase, and integrate Metabase with other applications. n8n has built-in support for a wide range of Metabase features, including adding, and getting alerts, databases, metrics, and questions. 

On this page, you'll find a list of operations the Metabase node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Metabase credentials](../credentials/metabase.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Alert
    * Get
    * Get All
* Database
    * Add
    * Get All
    * Get Fields
* Metric
    * Get
    * Get All
* Question
    * Get
    * Get All
    * Result Data

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Metabase node documentation integration templates](https://n8n.io/integrations/metabase) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
