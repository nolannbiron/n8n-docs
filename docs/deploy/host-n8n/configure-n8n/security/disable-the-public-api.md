---
title: Disable the public REST API
contentType: howto
nodeTitle: Disable the public API
originalFilePath: hosting/securing/disable-public-api.md
originalUrl: https://docs.n8n.io/hosting/securing/disable-public-api
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/security/disable-the-public-api
description: Disable the n8n public REST API to prevent others from using it.
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

# Disable the public API

The [n8n public REST API](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/n8n-api) allows you to programmatically perform many of the same tasks as you can in the n8n GUI.

If you don't plan on using this API, n8n recommends disabling it to improve the security of your n8n installation.

To disable the [public REST API](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/n8n-api), set the `N8N_PUBLIC_API_DISABLED` environment variable to `true`, for example:

```bash
export N8N_PUBLIC_API_DISABLED=true
```

## Disable the API playground <a href="#disable-the-api-playground" id="disable-the-api-playground"></a>

To disable the [API playground](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/n8n-api/use-an-api-playground), set the `N8N_PUBLIC_API_SWAGGERUI_DISABLED` environment variable to `true`, for example:

```bash
export N8N_PUBLIC_API_SWAGGERUI_DISABLED=true
```

## Related resources <a href="#related-resources" id="related-resources"></a>

* [Security](./): audit, harden, and restrict a self-hosted instance.
* [Deployment environment variables](../basic-configuration/use-environment-variables/deployment.md): more information on these environment variables.
* [Configuration](../basic-configuration/): how to set environment variables.
