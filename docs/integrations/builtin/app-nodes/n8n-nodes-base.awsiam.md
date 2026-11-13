---
title: AWS IAM node documentation
contentType:
  - integration
  - reference
nodeTitle: AWS IAM node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.awsiam.md
originalUrl: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awsiam
url: https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.awsiam
description: >-
  Learn how to use the AWS IAM node in n8n. Follow technical documentation to
  integrate AWS IAM node into your workflows.
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

# AWS IAM

Use the AWS IAM node to automate work in AWS Identity and Access Management (IAM) and integrate AWS IAM with other applications. n8n has built-in support for a wide range of AWS IAM features, which includes creating, updating, getting and deleting users and groups as well as managing group membership.

On this page, you'll find a list of operations the AWS IAM node supports, and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to the [AWS credentials documentation](../credentials/aws.md) for authentication information for this node.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* **User**:
  * **Add to Group**: Add an existing user to a group.
  * **Create**: Create a new user.
  * **Delete**: Delete a user.
  * **Get**: Retrieve a user.
  * **Get Many**: Retrieve a list of users.
  * **Remove From Group**: Remove a user from a group.
  * **Update**: Update an existing user.
* **Group**:
  * **Create**: Create a new group.
  * **Delete**: Create a new group.
  * **Get**: Retrieve a group.
  * **Get Many**: Retrieve a list of groups.
  * **Update**: Update an existing group.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>

[Browse AWS IAM node documentation integration templates](https://n8n.io/integrations/aws-iam) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to the [AWS IAM documentation](https://docs.aws.amazon.com/IAM/latest/APIReference/welcome.html) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to call the service's API.

You can use the credential you created for this service in the HTTP Request node:

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
2. Select the service you want to connect to.
3. Select your credential.

Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) for more information.
