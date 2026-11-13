---
title: Strava node documentation
description: >-
  Learn how to use the Strava node in n8n. Follow technical documentation to
  integrate Strava node into your workflows.
contentType:
  - integration
  - reference
nodeTitle: Strava node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.strava.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.strava'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.strava'
layout:
  description:
    visible: false
---

# Strava node <a href="#strava-node" id="strava-node"></a>

Use the Strava node to automate work in Strava, and integrate Strava with other applications. n8n has built-in support for a wide range of Strava features, including creating new activities, and getting activity information. 

On this page, you'll find a list of operations the Strava node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Strava credentials](../credentials/strava.md) for guidance on setting up authentication.
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Activity
    * Create a new activity
    * Get an activity
    * Get all activities
    * Get all activity comments
    * Get all activity kudos
    * Get all activity laps
    * Get all activity zones
    * Update an activity

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Strava node documentation integration templates](https://n8n.io/integrations/strava) or [search all templates](https://n8n.io/workflows/)

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
