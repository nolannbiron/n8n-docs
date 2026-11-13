---
title: Binary data environment variables
contentType: reference
hide:
  - toc
  - tags
nodeTitle: Binary data
originalFilePath: hosting/configuration/environment-variables/binary-data.md
originalUrl: https://docs.n8n.io/hosting/configuration/environment-variables/binary-data
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/basic-configuration/use-environment-variables/binary-data
description: >-
  Customize binary data storage modes and paths with environment variables for
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

# Binary data

{% hint style="info" %}
**File-based configuration**

You can add `_FILE` to individual variables to provide their configuration in a separate file. Refer to [Keeping sensitive data in separate files](../#keeping-sensitive-data-in-separate-files) for more details.
{% endhint %}

By default, n8n uses memory to store binary data. On self-hosted Business and Enterprise plans, you can choose to use an external service instead. Refer to [External storage](../../scaling/use-external-storage.md) for more information on using external storage for binary data.

| Variable                                 | Type   | Default                      | Description                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---------------------------------------- | ------ | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `N8N_AVAILABLE_BINARY_DATA_MODES`        | String | `filesystem`                 | A comma separated list of available binary data modes.                                                                                                                                                                                                                                                                                                                                                                                           |
| `N8N_BINARY_DATA_DATABASE_MAX_FILE_SIZE` | Number | `512`                        | Maximum size (in MiB) of a single file n8n stores when `N8N_DEFAULT_BINARY_DATA_MODE` is `database`. Can't exceed `1024`, the limit of a database column. Storing a larger file fails.                                                                                                                                                                                                                                                           |
| `N8N_BINARY_DATA_STORAGE_PATH`           | String | `N8N_USER_FOLDER/binaryData` | The path where n8n stores binary data.                                                                                                                                                                                                                                                                                                                                                                                                           |
| `N8N_DEFAULT_BINARY_DATA_MODE`           | String | `default`                    | The default binary data mode. `default` keeps binary data in memory. Set to `filesystem` to use the filesystem, `s3` to use AWS S3, `azure` to use Azure Blob Storage, or `database` to use the DB. Note that binary data pruning operates on the active binary data mode. For example, if your instance stored data in S3, and you later switched to filesystem mode, n8n only prunes binary data in the filesystem. This may change in future. |

## Related resources

* [Environment variables](./)
