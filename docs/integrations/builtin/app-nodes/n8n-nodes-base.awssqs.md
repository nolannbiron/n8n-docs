---
title: AWS SQS node documentation
description: >-
  Learn how to use the AWS SQS node in n8n. Follow technical documentation to
  integrate AWS SQS node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: AWS SQS node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.awssqs.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awssqs'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awssqs'
layout:
  description:
    visible: false
---

# AWS SQS node <a href="#aws-sqs-node" id="aws-sqs-node"></a>

Use the AWS SQS node to automate work in AWS SNS, and integrate AWS SQS with other applications. n8n has built-in support for a wide range of AWS SQS features, including sending messages.

On this page, you'll find a list of operations the AWS SQS node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to  [AWS SQS credentials](../credentials/aws.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Send a message to a queue.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse AWS SQS node documentation integration templates](https://n8n.io/integrations/aws-sqs) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.

