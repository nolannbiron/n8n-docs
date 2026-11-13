---
title: Auth0 Management credentials
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Auth0 Management credentials
originalFilePath: integrations/builtin/credentials/auth0management.md
originalUrl: https://docs.n8n.io/integrations/builtin/credentials/auth0management
url: https://docs.n8n.io/integrations/builtin/credentials/auth0management
description: >-
  Documentation for the Auth0 Management credentials. Use these credentials to
  authenticate Auth0 Management in n8n, a workflow automation platform.
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

# Auth0 Management credentials

You can use these credentials to authenticate when using the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to make a [Custom API call](../custom-api-actions-for-existing-nodes.md).

## Prerequisites <a href="#prerequisites" id="prerequisites"></a>

Create an [Auth0](https://auth0.com) account.

## Supported authentication methods <a href="#supported-authentication-methods" id="supported-authentication-methods"></a>

* API client secret

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Auth0 Management's documentation](https://auth0.com/docs/api/management/v2) for more information about the service.

This is a credential-only node. Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) to learn more. View [example workflows and related content](https://n8n.io/integrations/auth0-management-api/) on n8n's website.

## Using API client secret <a href="#using-api-client-secret" id="using-api-client-secret"></a>

To configure this credential, you'll need:

* An Auth0 **Domain**
* A **Client ID**
* A **Client Secret**

Refer to the [Auth0 Management API Get Access Tokens documentation](https://auth0.com/docs/secure/tokens/access-tokens/get-access-tokens) for instructions on obtaining the Client ID and Client Secret from the application's **Settings** tab.
