---
title: Timezone and localization environment variables
contentType: reference
hide:
  - toc
  - tags
nodeTitle: Timezone and localization
originalFilePath: hosting/configuration/environment-variables/timezone-localization.md
originalUrl: >-
  https://docs.n8n.io/hosting/configuration/environment-variables/timezone-localization
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/basic-configuration/use-environment-variables/timezone-and-localization
description: Set the timezone and default language locale for self-hosted n8n instance.
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

# Timezone and localization

{% hint style="info" %}
**File-based configuration**

You can add `_FILE` to individual variables to provide their configuration in a separate file. Refer to [Keeping sensitive data in separate files](../#keeping-sensitive-data-in-separate-files) for more details.
{% endhint %}

| Variable             | Type   | Default            | Description                                                                                                                                                                                                                                                                                                                                                    |
| -------------------- | ------ | ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `GENERIC_TIMEZONE`   | \*     | `America/New_York` | The n8n instance timezone. Important for schedule nodes (such as Cron).                                                                                                                                                                                                                                                                                        |
| `N8N_DEFAULT_LOCALE` | String | `en`               | A locale identifier, compatible with the [Accept-Language header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-Language). n8n doesn't support regional identifiers, such as `de-AT`. When running in a locale other than the default, n8n displays UI strings in the selected locale, and falls back to `en` for any untranslated strings. |

## Related resources

* [Environment variables](./)
