---
title: Supabase node documentation
description: >-
  Learn how to use the Supabase node in n8n. Follow technical documentation to
  integrate Supabase node into your workflows.
contentType:
  - integration
  - reference
priority: high
nodeTitle: n8n-nodes-base.supabase
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.supabase/index.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.supabase'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.supabase'
layout:
  description:
    visible: false
---

# Supabase node <a href="#supabase-node" id="supabase-node"></a>

Use the Supabase node to automate work in Supabase, and integrate Supabase with other applications. n8n has built-in support for a wide range of Supabase features, including creating, deleting, and getting rows. 

On this page, you'll find a list of operations the Supabase node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Supabase credentials](../../credentials/supabase.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Row
    * Create a new row
    * Delete a row
    * Get a row
    * Get all rows
    * Update a row

## Using custom schemas <a href="#using-custom-schemas" id="using-custom-schemas"></a>

By default, the Supabase node only fetches the `public` schema. To fetch [custom schemas](https://supabase.com/docs/guides/api/using-custom-schemas), enable **Use Custom Schema**.

In the new **Schema** field, provide the custom schema the Supabase node should use.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse n8n-nodes-base.supabase integration templates](https://n8n.io/integrations/supabase) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

## Common issues <a href="#common-issues" id="common-issues"></a>

For common errors or issues and suggested resolution steps, refer to [Common issues](common-issues.md).
