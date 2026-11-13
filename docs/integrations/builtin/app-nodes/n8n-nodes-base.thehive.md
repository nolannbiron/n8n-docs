---
title: TheHive node documentation
contentType:
  - integration
  - reference
nodeTitle: TheHive node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.thehive.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.thehive
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.thehive
description: >-
  Learn how to use the TheHive node in n8n. Follow technical documentation to
  integrate TheHive node into your workflows.
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

# TheHive

Use the TheHive node to automate work in TheHive, and integrate TheHive with other applications. n8n has built-in support for a wide range of TheHive features, including creating alerts, counting tasks logs, cases, and observables.

On this page, you'll find a list of operations the TheHive node supports and links to more resources.

{% hint style="info" %}
**TheHive and TheHive 5**

n8n provides two nodes for TheHive. Use this node (TheHive) if you want to use TheHive's version 3 or 4 API. If you want to use version 5, use [TheHive 5](n8n-nodes-base.thehive5.md).
{% endhint %}

{% hint style="info" %}
**Credentials**

Refer to [TheHive credentials](../credentials/thehive.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

The available operations depend on your API version. To see the operations list, create your credentials, including selecting your API version. Then return to the node, select the resource you want to use, and n8n displays the available operations for your API version.

* Alert
* Case
* Log
* Observable
* Task

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse TheHive node documentation integration templates](https://n8n.io/integrations/thehive) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.

## Related resources <a href="#related-resources" id="related-resources"></a>

n8n provides a trigger node for TheHive. Refer to the [TheHive Trigger node documentation](../trigger-nodes/n8n-nodes-base.thehivetrigger.md) for more information.

Refer to TheHive's documentation for more information about the service:

* The API docs for TheHive 3 and 4 are no longer online. Refer to the [TheHive 5 API documentation](https://docs.strangebee.com/thehive/api-docs/) for the current API.
* [Cortex API guide](https://docs.strangebee.com/cortex/api/api-guide/), for Cortex, the analysis engine that works with TheHive.
