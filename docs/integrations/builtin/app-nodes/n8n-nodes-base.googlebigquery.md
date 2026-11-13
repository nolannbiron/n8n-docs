---
title: Google BigQuery node documentation
description: >-
  Learn how to use the Google BigQuery node in n8n. Follow technical
  documentation to integrate Google BigQuery node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Google BigQuery node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googlebigquery.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlebigquery
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlebigquery
layout:
  description:
    visible: false
---

# Google BigQuery node <a href="#google-bigquery-node" id="google-bigquery-node"></a>

Use the Google BigQuery node to automate work in Google BigQuery, and integrate Google BigQuery with other applications. n8n has built-in support for a wide range of Google BigQuery features, including creating, and retrieving records.

On this page, you'll find a list of operations the Google BigQuery node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Google BigQuery credentials](../credentials/google/README.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

- Execute Query
- Insert

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Google BigQuery node documentation integration templates](https://n8n.io/integrations/google-bigquery) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Google BigQuery's documentation](https://cloud.google.com/bigquery/docs/reference/rest) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
