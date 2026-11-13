---
title: LoneScale node documentation
description: >-
  Learn how to use the LoneScale node in n8n. Follow technical documentation to
  integrate LoneScale node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: LoneScale node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.lonescale.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.lonescale'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.lonescale'
layout:
  description:
    visible: false
---

# LoneScale node <a href="#lonescale-node" id="lonescale-node"></a>

Use the LoneScale node to automate work in LoneScale and integrate LoneScale with other applications. n8n has built-in support for managing Lists and Items in LoneScale. 

On this page, you'll find a list of operations the LoneScale node supports, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [LoneScale credentials documentation](../credentials/lonescale.md) for authentication information for this node.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* List
	* Create
* Item
	* Create

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse LoneScale node documentation integration templates](https://n8n.io/integrations/lonescale) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [LoneScales documentation](https://help-center.lonescale.com/en/articles/6454360-lonescale-public-api) for more information about the service.

n8n provides a trigger node for LoneScale. Refer to the [LoneScale Trigger node documentation](../trigger-nodes/n8n-nodes-base.lonescaletrigger.md) for more information.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
