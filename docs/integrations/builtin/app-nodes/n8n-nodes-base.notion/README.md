---
title: Notion node documentation
contentType:
  - integration
  - reference
priority: high
nodeTitle: n8n-nodes-base.notion
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.notion/index.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.notion
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.notion
description: >-
  Learn how to use the Notion node in n8n. Follow technical documentation to
  integrate Notion node into your workflows.
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

# Notion

Use the Notion node to automate work in Notion, and integrate Notion with other applications. n8n has built-in support for a wide range of Notion features, including getting and searching databases, creating pages, and getting users.

On this page, you'll find a list of operations the Notion node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Notion credentials](../../credentials/notion.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Block
  * Append After
  * Get Many
  * Get Markdown
* Data Source
  * Get
  * Search
* Database
  * Get
* Database Page
  * Create
  * Get
  * Get Many
  * Update
* Page
  * Archive
  * Create
  * Get Markdown
  * Search
  * Update Markdown
* User
  * Get
  * Get Many

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse n8n-nodes-base.notion integration templates](https://n8n.io/integrations/notion) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

n8n provides an app node for Notion. Refer to the [Notion Trigger node documentation](../../trigger-nodes/n8n-nodes-base.notiontrigger.md) for more information.

Refer to [Notion's documentation](https://developers.notion.com/) for details about their API.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../../custom-api-actions-for-existing-nodes.md) for more information.

## Common issues <a href="#common-issues" id="common-issues"></a>

For common errors or issues and suggested resolution steps, refer to [Common issues](common-issues.md).
