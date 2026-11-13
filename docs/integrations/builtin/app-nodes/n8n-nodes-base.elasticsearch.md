---
title: Elasticsearch node documentation
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Elasticsearch node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.elasticsearch.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.elasticsearch
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.elasticsearch
description: >-
  Learn how to use the Elasticsearch node in n8n. Follow technical documentation
  to integrate Elasticsearch node into your workflows.
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

# Elasticsearch

Use the Elasticsearch node to automate work in Elasticsearch, and integrate Elasticsearch with other applications. n8n has built-in support for a wide range of Elasticsearch features, including creating, updating, deleting, and getting documents and indexes.

On this page, you'll find a list of operations the Elasticsearch node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Elasticsearch credentials](../credentials/elasticsearch.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Document
  * Create a document
  * Delete a document
  * Get a document
  * Get all documents
  * Update a document
* Index
  * Create
  * Delete
  * Get
  * Get All

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Elasticsearch node documentation integration templates](https://n8n.io/integrations/elasticsearch) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
