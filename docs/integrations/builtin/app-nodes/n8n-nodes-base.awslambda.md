---
title: AWS Lambda node documentation
description: >-
  Learn how to use the AWS Lambda node in n8n. Follow technical documentation to
  integrate AWS Lambda node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: AWS Lambda node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.awslambda.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awslambda'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awslambda'
layout:
  description:
    visible: false
---

# AWS Lambda node <a href="#aws-lambda-node" id="aws-lambda-node"></a>

Use the AWS Lambda node to automate work in AWS Lambda, and integrate AWS Lambda with other applications. n8n has built-in support for a wide range of AWS Lambda features, including invoking functions.

On this page, you'll find a list of operations the AWS Lambda node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [AWS Lambda credentials](../credentials/aws.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Invoke a function

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse AWS Lambda node documentation integration templates](https://n8n.io/integrations/aws-lambda) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.

