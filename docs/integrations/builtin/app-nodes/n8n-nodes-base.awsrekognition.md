---
title: AWS Rekognition node documentation
description: >-
  Learn how to use the AWS Rekognition node in n8n. Follow technical
  documentation to integrate AWS Rekognition node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: AWS Rekognition node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.awsrekognition.md
originalUrl: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awsrekognition
url: >-
  https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awsrekognition
layout:
  description:
    visible: false
---

# AWS Rekognition node <a href="#aws-rekognition-node" id="aws-rekognition-node"></a>

Use the AWS Rekognition node to automate work in AWS Rekognition, and integrate AWS Rekognition with other applications. n8n has built-in support for a wide range of AWS Rekognition features, including analyzing images.

On this page, you'll find a list of operations the AWS Rekognition node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [AWS Rekognition credentials](../credentials/aws.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

**Image**

- Analyze

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse AWS Rekognition node documentation integration templates](https://n8n.io/integrations/aws-rekognition) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.

