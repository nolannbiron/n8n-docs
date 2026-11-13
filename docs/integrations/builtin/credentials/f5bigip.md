---
title: F5 Big-IP credentials
contentType:
  - integration
  - reference
priority: medium
nodeTitle: F5 Big-IP credentials
originalFilePath: integrations/builtin/credentials/f5bigip.md
originalUrl: https://docs.n8n.io/integrations/builtin/credentials/f5bigip
url: https://docs.n8n.io/integrations/builtin/credentials/f5bigip
description: >-
  Documentation for the F5 Big-IP credentials. Use these credentials to
  authenticate F5 Big-IP in n8n, a workflow automation platform.
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

# F5 Big-IP credentials

You can use these credentials to authenticate when using the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to make a [Custom API call](../custom-api-actions-for-existing-nodes.md).

## Prerequisites <a href="#prerequisites" id="prerequisites"></a>

Create an [F5 Big-IP](https://www.f5.com/products/big-ip-services) account.

## Authentication methods <a href="#authentication-methods" id="authentication-methods"></a>

* Account login

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [F5 Big-IP's API documentation](https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/) for more information about the service.

This is a credential-only node. Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) to learn more. View [example workflows and related content](https://n8n.io/integrations/f5-big-ip/) on n8n's website.

## Using account login <a href="#using-account-login" id="using-account-login"></a>

To configure this credential, you'll need:

* A **Username**: Use the username you use to log in to F5 Big-IP.
* A **Password**: Use the user password you use to log in to F5 Big-IP.
