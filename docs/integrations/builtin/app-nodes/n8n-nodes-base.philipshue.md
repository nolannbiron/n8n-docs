---
title: Philips Hue node documentation
contentType:
  - integration
  - reference
nodeTitle: Philips Hue node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.philipshue.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.philipshue
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.philipshue
description: >-
  Learn how to use the Philips Hue node in n8n. Follow technical documentation
  to integrate Philips Hue node into your workflows.
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

# Philips Hue

Use the Philips Hue node to automate work in Philips Hue, and integrate Philips Hue with other applications. n8n has built-in support for a wide range of Philips Hue features, including deleting, retrieving, and updating lights.

On this page, you'll find a list of operations the Philips Hue node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Philips Hue credentials](../credentials/philipshue.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Light
  * Delete a light
  * Retrieve a light
  * Retrieve all lights
  * Update a light

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse Philips Hue node documentation integration templates](https://n8n.io/integrations/philips-hue) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
