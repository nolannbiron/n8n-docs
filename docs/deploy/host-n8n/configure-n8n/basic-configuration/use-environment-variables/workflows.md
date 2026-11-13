---
title: Workflows environment variables
contentType: reference
hide:
  - toc
  - tags
nodeTitle: Workflows
originalFilePath: hosting/configuration/environment-variables/workflows.md
originalUrl: https://docs.n8n.io/hosting/configuration/environment-variables/workflows
url: >-
  https://docs.n8n.io/deploy/host-n8n/configure-n8n/basic-configuration/use-environment-variables/workflows
description: >-
  Environment variables to configure workflows in n8n, including default naming,
  onboarding flow preferences, tag management, and caller policy settings.
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

# Workflows

{% hint style="info" %}
**File-based configuration**

You can add `_FILE` to individual variables to provide their configuration in a separate file. Refer to [Keeping sensitive data in separate files](../#keeping-sensitive-data-in-separate-files) for more details.
{% endhint %}

| Variable                                    | Type    | Default                  | Description                                                                                                                                                                                                                                   |
| ------------------------------------------- | ------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `N8N_ONBOARDING_FLOW_DISABLED`              | Boolean | `false`                  | Whether to disable onboarding tips when creating a new workflow (true) or not (false).                                                                                                                                                        |
| `N8N_WORKFLOW_ACTIVATION_BATCH_SIZE`        | Number  | `1`                      | How many workflows to publish simultaneously during startup.                                                                                                                                                                                  |
| `N8N_WORKFLOW_CALLER_POLICY_DEFAULT_OPTION` | String  | `workflowsFromSameOwner` | Which workflows can call a workflow. Options are: `any`, `none`, `workflowsFromAList`, `workflowsFromSameOwner`. This feature requires [Workflow sharing](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/manage-workflows/share-with-others). |
| `N8N_WORKFLOW_TAGS_DISABLED`                | Boolean | `false`                  | Whether to disable workflow tags (true) or enable tags (false).                                                                                                                                                                               |
| `WORKFLOWS_DEFAULT_NAME`                    | String  | `My workflow`            | The default name used for new workflows.                                                                                                                                                                                                      |

## Related resources

* [Environment variables](./)
