---
title: External hooks environment variables
description: >-
  Environment variables to integrate external hooks into your self-hosted n8n
  instance.
contentType: reference
tags:
  - environment variables
hide:
  - toc
  - tags
nodeTitle: External hooks
originalFilePath: hosting/configuration/environment-variables/external-hooks.md
originalUrl: 'https://docs.n8n.io/hosting/configuration/environment-variables/external-hooks'
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/basic-configuration/use-environment-variables/external-hooks
layout:
  description:
    visible: false
---

# External hooks environment variables <a href="#external-hooks-environment-variables" id="external-hooks-environment-variables"></a>

{% hint style="info" %}
**File-based configuration**

You can add `_FILE` to individual variables to provide their configuration in a separate file. Refer to [Keeping sensitive data in separate files](https://app.gitbook.com/s/CVqOCDXNeshWSm0VR543/host-n8n/configure-n8n/basic-configuration#keeping-sensitive-data-in-separate-files) for more details.
{% endhint %}

You can define external hooks that n8n executes whenever a specific operation runs. Refer to [External hooks](../../external-hooks.md) for the full reference, including available hooks and file formatting.

| Variable | Type  | Default | Description |
| :------- | :---- | :------ | :---------- |
| `EXTERNAL_HOOK_FILES` | String | - | Files containing backend external hooks. Provide multiple files separated by the character defined in `EXTERNAL_HOOK_FILES_SEPARATOR`. |
| `EXTERNAL_HOOK_FILES_SEPARATOR` | String | `:` | Separator character for `EXTERNAL_HOOK_FILES`. Use `;` on Windows to avoid conflicts with drive-letter paths like `C:\`. |
| `EXTERNAL_FRONTEND_HOOKS_URLS` | String | - | URLs to files containing frontend external hooks. Provide multiple URLs as a colon-separated list ("`:`"). |

## Related resources

* [Environment variables](./)
