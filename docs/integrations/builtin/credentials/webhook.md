---
title: Webhook credentials
contentType:
  - integration
  - reference
priority: critical
nodeTitle: Webhook credentials
originalFilePath: integrations/builtin/credentials/webhook.md
originalUrl: https://docs.n8n.io/integrations/builtin/credentials/webhook
url: https://docs.n8n.io/integrations/builtin/credentials/webhook
description: >-
  Documentation for Webhook credentials. Use these credentials to authenticate
  Webhook in n8n, a workflow automation platform.
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

# Webhook credentials

You can use these credentials to authenticate the following nodes:

* [Webhook](../core-nodes/n8n-nodes-base.webhook/)

## Prerequisites <a href="#prerequisites" id="prerequisites"></a>

You must use the authentication method required by the app or service you want to query.

## Supported authentication methods <a href="#supported-authentication-methods" id="supported-authentication-methods"></a>

* Basic auth
* Header auth
* JWT auth
* None

## Using basic auth <a href="#using-basic-auth" id="using-basic-auth"></a>

Use this generic authentication if your app or service supports basic authentication.

To configure this credential, enter:

* The **Username** you use to access the app or service your HTTP Request is targeting
* The **Password** that goes with that username

## Using header auth <a href="#using-header-auth" id="using-header-auth"></a>

Use this generic authentication if your app or service supports header authentication.

To configure this credential, enter:

* The header **Name** you need to pass to the app or service your HTTP request is targeting
* The **Value** for the header

Read more about [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers#authentication)

## Using JWT auth <a href="#using-jwt-auth" id="using-jwt-auth"></a>

[**JWT Auth**](https://jwt.io/introduction/) is a method of authentication that uses JSON Web Tokens (JWT) to digitally sign data. This authentication method uses the **JWT credential** and can use either a **Passphrase** or **PEM Key** as key type. Refer to [JWT credential](jwt.md) for more information.
