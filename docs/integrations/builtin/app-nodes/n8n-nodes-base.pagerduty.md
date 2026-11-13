---
title: PagerDuty node documentation
description: >-
  Learn how to use the PagerDuty node in n8n. Follow technical documentation to
  integrate PagerDuty node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: PagerDuty node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.pagerduty.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.pagerduty'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.pagerduty'
layout:
  description:
    visible: false
---

# PagerDuty node <a href="#pagerduty-node" id="pagerduty-node"></a>

Use the PagerDuty node to automate work in PagerDuty, and integrate PagerDuty with other applications. n8n has built-in support for a wide range of PagerDuty features, including creating incident notes, as well as updating, and getting all log entries and users. 

On this page, you'll find a list of operations the PagerDuty node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [PagerDuty credentials](../credentials/pagerduty.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Incident
    * Create an incident
    * Get an incident
    * Get all incidents
    * Update an incident
* Incident Note
    * Create an incident note
    * Get all incident's notes
* Log Entry
    * Get a log entry
    * Get all log entries
* User
    * Get a user

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse PagerDuty node documentation integration templates](https://n8n.io/integrations/pagerduty) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.


