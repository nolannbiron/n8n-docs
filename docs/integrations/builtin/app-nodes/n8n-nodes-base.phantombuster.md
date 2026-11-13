---
title: PhantomBuster node documentation
contentType:
  - integration
  - reference
nodeTitle: PhantomBuster node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.phantombuster.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.phantombuster
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.phantombuster
description: >-
  Learn how to use the PhantomBuster node in n8n. Follow technical documentation
  to integrate PhantomBuster node into your workflows.
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

# PhantomBuster

Use the PhantomBuster node to automate work in PhantomBuster, and integrate PhantomBuster with other applications. n8n has built-in support for a wide range of PhantomBuster features, including adding, deleting, and getting agents.

On this page, you'll find a list of operations the PhantomBuster node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [PhantomBuster credentials](../credentials/phantombuster.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Agent
  * Delete an agent by ID.
  * Get an agent by ID.
  * Get all agents of the current user's organization.
  * Get the output of the most recent container of an agent.
  * Add an agent to the launch queue.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse PhantomBuster node documentation integration templates](https://n8n.io/integrations/phantombuster) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
