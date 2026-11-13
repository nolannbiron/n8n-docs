---
title: Gong node documentation
description: >-
  Learn how to use the Gong node in n8n. Follow technical documentation to
  integrate Gong node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Gong node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.gong.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.gong'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.gong'
layout:
  description:
    visible: false
---

# Gong node <a href="#gong-node" id="gong-node"></a>

Use the Gong node to automate work in Gong and integrate Gong with other applications. n8n has built-in support for a wide range of Gong features, which includes getting one or more calls and users.

On this page, you'll find a list of operations the Gong node supports, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [Gong credentials documentation](../credentials/gong.md) for authentication information for this node.
{% endhint %}


## Operations <a href="#operations" id="operations"></a>


* Call
	* Get
	* Get Many
* User
	* Get
	* Get Many


## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Gong node documentation integration templates](https://n8n.io/integrations/gong) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Gong's documentation](https://gong.app.gong.io/settings/api/documentation) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
