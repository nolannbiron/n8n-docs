---
title: AWS SNS node documentation
description: >-
  Learn how to use the AWS SNS node in n8n. Follow technical documentation to
  integrate AWS SNS node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: AWS SNS node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.awssns.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awssns'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awssns'
layout:
  description:
    visible: false
---

# AWS SNS node <a href="#aws-sns-node" id="aws-sns-node"></a>

Use the AWS SNS node to automate work in AWS SNS, and integrate AWS SNS with other applications. n8n has built-in support for a wide range of AWS SNS features, including publishing messages.

On this page, you'll find a list of operations the AWS SNS node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [AWS SNS credentials](../credentials/aws.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Publish a message to a topic

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse AWS SNS node documentation integration templates](https://n8n.io/integrations/aws-sns) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

