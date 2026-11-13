---
title: DFIR-IRIS credentials
contentType:
  - integration
  - reference
nodeTitle: DFIR-IRIS credentials
originalFilePath: integrations/builtin/credentials/dfiriris.md
originalUrl: https://docs.n8n.io/integrations/builtin/credentials/dfiriris
url: https://docs.n8n.io/integrations/builtin/credentials/dfiriris
description: >-
  Documentation for the DFIR-IRIS credentials. Use these credentials to
  authenticate DFIR-IRIS in n8n, a workflow automation platform.
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

# DFIR-IRIS credentials

You can use these credentials to authenticate when using the [HTTP Request node](../core-nodes/n8n-nodes-base.httprequest/) to make a [Custom API call](../custom-api-actions-for-existing-nodes.md).

## Prerequisites <a href="#prerequisites" id="prerequisites"></a>

An accessible instance of [DFIR-IRIS](https://docs.dfir-iris.org/latest/getting_started/).

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [DFIR-IRIS's API documentation](https://docs.dfir-iris.org/operations/api/) for more information about authenticating with the service.

This is a credential-only node. Refer to [Custom API operations](../custom-api-actions-for-existing-nodes.md) to learn more. View [example workflows and related content](https://n8n.io/integrations/iris-dfir/) on n8n's website.

## Using API Key <a href="#using-api-key" id="using-api-key"></a>

To configure this credential, you'll need:

* An **API Key**: Refer to [DFIR-IRIS's API documentation](https://docs.dfir-iris.org/operations/api/) for instructions on getting your API key.
* The **Base URL** of your DFIR-IRIS instance.
