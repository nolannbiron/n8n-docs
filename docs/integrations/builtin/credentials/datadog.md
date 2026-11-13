---
title: Datadog credentials
contentType:
  - integration
  - reference
nodeTitle: Datadog credentials
originalFilePath: integrations/builtin/credentials/datadog.md
originalUrl: https://docs.n8n.io/integrations/builtin/credentials/datadog
url: https://docs.n8n.io/integrations/builtin/credentials/datadog
description: >-
  Documentation for the Datadog credentials. Use these credentials to
  authenticate Datadog in n8n, a workflow automation platform.
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

# Datadog credentials

You can use these credentials to authenticate when using the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to make a [Custom API call](../custom-api-actions-for-existing-nodes.md).

## Prerequisites <a href="#prerequisites" id="prerequisites"></a>

Create a [Datadog](https://app.datadoghq.eu/signup) account.

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Datadog's API documentation](https://docs.datadoghq.com/api/latest/) for more information about authenticating with the service.

This is a credential-only node. Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) to learn more. View [example workflows and related content](https://n8n.io/integrations/datadog/) on n8n's website.

## Using API Key <a href="#using-api-key" id="using-api-key"></a>

To configure this credential, you'll need:

* Your Datadog instance **Host**
* An **API Key**
* An **App Key**

Refer to [Authentication](https://docs.datadoghq.com/api/latest/authentication/) on Datadog's website for more information.
