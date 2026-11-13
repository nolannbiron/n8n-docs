---
title: Google Translate node documentation
description: >-
  Learn how to use the Google Translate node in n8n. Follow technical
  documentation to integrate Google Translate node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Google Translate node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googletranslate.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googletranslate
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googletranslate
layout:
  description:
    visible: false
---

# Google Translate node <a href="#google-translate-node" id="google-translate-node"></a>

Use the Google Translate node to automate work in Google Translate, and integrate Google Translate with other applications. n8n has built-in support for a wide range of Google Translate features, including translating languages.

On this page, you'll find a list of operations the Google Translate node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Google Translate credentials](../credentials/google/README.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Language
    * Translate data

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Google Translate node documentation integration templates](https://n8n.io/integrations/google-translate) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
