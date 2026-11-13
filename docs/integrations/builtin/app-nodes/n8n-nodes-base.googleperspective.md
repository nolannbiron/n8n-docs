---
title: Google Perspective node documentation
contentType:
  - integration
  - reference
nodeTitle: Google Perspective node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googleperspective.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googleperspective
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googleperspective
description: >-
  Learn how to use the Google Perspective node in n8n. Follow technical
  documentation to integrate Google Perspective node into your workflows.
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

# Google Perspective

Use the Google Perspective node to automate work in Google Perspective, and integrate Google Perspective with other applications. n8n has built-in support for a wide range of Google Perspective features, including analyzing comments.

On this page, you'll find a list of operations the Google Perspective node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Google Perspective credentials](../credentials/google/) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Analyze Comment

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Google Perspective node documentation integration templates](https://n8n.io/integrations/google-perspective) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
