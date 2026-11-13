---
title: Source control environment variables
contentType: reference
hide:
  - toc
  - tags
nodeTitle: Source control
originalFilePath: hosting/configuration/environment-variables/source-control.md
originalUrl: https://docs.n8n.io/hosting/configuration/environment-variables/source-control
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/basic-configuration/use-environment-variables/source-control
description: Environment variable to set the default SSH key type for source control setup.
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

# Source control

{% hint style="info" %}
**File-based configuration**

You can add `_FILE` to individual variables to provide their configuration in a separate file. Refer to [Keeping sensitive data in separate files](../#keeping-sensitive-data-in-separate-files) for more details.
{% endhint %}

n8n uses Git-based source control to support environments. Refer to [Source control and environments](https://app.gitbook.com/s/nd4xCXTdU07PkJJRhaDG/use-source-control-and-environments/set-up-source-control) for more information on how to link a Git repository to an n8n instance and configure your source control.

| Variable                                 | Type   | Default   | Description                                                                                                                                                                             |
| ---------------------------------------- | ------ | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `N8N_SOURCECONTROL_DEFAULT_SSH_KEY_TYPE` | String | `ed25519` | Set to `rsa` to make RSA the default SSH key type for [Source control setup](https://app.gitbook.com/s/nd4xCXTdU07PkJJRhaDG/use-source-control-and-environments/set-up-source-control). |

## Related resources

* [Environment variables](./)
