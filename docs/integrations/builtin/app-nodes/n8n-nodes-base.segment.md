---
title: Segment node documentation
description: >-
  Learn how to use the Segment node in n8n. Follow technical documentation to
  integrate Segment node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Segment node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.segment.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.segment'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.segment'
layout:
  description:
    visible: false
---

# Segment node <a href="#segment-node" id="segment-node"></a>

Use the Segment node to automate work in Segment, and integrate Segment with other applications. n8n has built-in support for a wide range of Segment features, including adding users to groups, creating identities, and tracking activities. 

On this page, you'll find a list of operations the Segment node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Segment credentials](../credentials/segment.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Group
    * Add a user to a group
* Identify
    * Create an identity
* Track
    * Record the actions your users perform. Every action triggers an event, which can also have associated properties.
    * Record page views on your website, along with optional extra information about the page being viewed.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Segment node documentation integration templates](https://n8n.io/integrations/segment) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
