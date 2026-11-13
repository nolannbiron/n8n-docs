---
title: Google Slides node documentation
description: >-
  Learn how to use the Google Slides node in n8n. Follow technical documentation
  to integrate Google Slides node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Google Slides node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googleslides.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googleslides'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googleslides'
layout:
  description:
    visible: false
---

# Google Slides node <a href="#google-slides-node" id="google-slides-node"></a>

Use the Google Slides node to automate work in Google Slides, and integrate Google Slides with other applications. n8n has built-in support for a wide range of Google Slides features, including creating presentations, and getting pages. 

On this page, you'll find a list of operations the Google Slides node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Google credentials](../credentials/google/README.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Page
    * Get a page
    * Get a thumbnail
* Presentation
    * Create a presentation
    * Get a presentation
    * Get presentation slides
    * Replace text in a presentation

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Google Slides node documentation integration templates](https://n8n.io/integrations/google-slides) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
