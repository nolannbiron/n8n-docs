---
title: Google Business Profile node documentation
description: >-
  Learn how to use the Google Business Profile node in n8n. Follow technical
  documentation to integrate Google Business Profile node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Google Business Profile node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.googlebusinessprofile.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlebusinessprofile
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.googlebusinessprofile
layout:
  description:
    visible: false
---

# Google Business Profile node <a href="#google-business-profile-node" id="google-business-profile-node"></a>

Use the Google Business Profile node to automate work in Google Business Profile and integrate Google Business Profile with other applications. n8n has built-in support for a wide range of Google Business Profile features, which includes creating, updating, and deleting posts and reviews.

On this page, you'll find a list of operations the Google Business Profile node supports, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [Google credentials documentation](../credentials/google/README.md) for authentication information for this node.
{% endhint %}


## Operations <a href="#operations" id="operations"></a>

* Post
	* Create
	* Delete
	* Get
	* Get Many
	* Update
* Review
	* Delete Reply
	* Get
	* Get Many
	* Reply

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Google Business Profile node documentation integration templates](https://n8n.io/integrations/google-business-profile) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

n8n provides a trigger node for Google Business Profile. Refer to the [Google Business Profile Trigger node documentation](../trigger-nodes/n8n-nodes-base.googlebusinessprofiletrigger.md) for more information.

Refer to [Google Business Profile's documentation](https://developers.google.com/my-business/reference/rest) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
