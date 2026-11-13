---
title: Credentials environment variables
contentType: reference
hide:
  - toc
  - tags
nodeTitle: Credentials
originalFilePath: hosting/configuration/environment-variables/credentials.md
originalUrl: https://docs.n8n.io/hosting/configuration/environment-variables/credentials
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/basic-configuration/use-environment-variables/credentials
description: >-
  Manage default credentials and override them through environment variables
  your self-hosted n8n instance.
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
tags:
  - environment variables
---

# Credentials

{% hint style="info" %}
**File-based configuration**

You can add `_FILE` to individual variables to provide their configuration in a separate file. Refer to [Keeping sensitive data in separate files](../#keeping-sensitive-data-in-separate-files) for more details.
{% endhint %}

Enable credential overwrites using the following environment variables. Refer to [Credential overwrites](https://app.gitbook.com/s/nd4xCXTdU07PkJJRhaDG/manage-credentials/credential-overwrites) for details.

| Variable                                                              | Type    | Default          | Description                                                                                                                                                               |
| --------------------------------------------------------------------- | ------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><code>CREDENTIALS_OVERWRITE_DATA</code><br>/<code>_FILE</code></p> | \*      | -                | Overwrites for credentials.                                                                                                                                               |
| `CREDENTIALS_OVERWRITE_ENDPOINT`                                      | String  | -                | The API endpoint to fetch credentials.                                                                                                                                    |
| `CREDENTIALS_OVERWRITE_PERSISTENCE`                                   | Boolean | `false`          | Enable database persistence for credential overwrites. Required for multi-instance or queue mode to propagate overwrites to workers through a publish/subscribe approach. |
| `N8N_MANAGED_OAUTH_SHOW_SCOPES`                                       | String  | -                | Comma-separated list of managed OAuth credential types for which users can configure scope fields.                                                                        |
| `CREDENTIALS_DEFAULT_NAME`                                            | String  | `My credentials` | The default name for credentials.                                                                                                                                         |

## Related resources

* [Environment variables](./)
