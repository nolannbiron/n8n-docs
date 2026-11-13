---
title: Twilio node documentation
description: >-
  Learn how to use the Twilio node in n8n. Follow technical documentation to
  integrate Twilio node into your workflows.
contentType:
  - integration
  - reference
priority: medium
nodeTitle: Twilio node documentation
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.twilio.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.twilio'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.twilio'
layout:
  description:
    visible: false
---

# Twilio node <a href="#twilio-node" id="twilio-node"></a>

Use the Twilio node to automate work in Twilio, and integrate Twilio with other applications. n8n supports sending MMS/SMS and WhatsApp messages with Twilio. 

On this page, you'll find a list of operations the Twilio node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [Twilio credentials](../credentials/twilio.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**This node can be used as an AI tool**

This node can be used to enhance the capabilities of an AI agent. When used in this way, many parameters can be set automatically, or with information directed by AI - find out more in the [AI tool parameters documentation](https://app.gitbook.com/s/rPN1zU5jaYNvwH7RzxqA/integrate-ai/ai-examples/use-ai-for-parameters).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* SMS
    * Send SMS/MMS/WhatsApp message
* Call
    * Make a phone call using text-to-speech to say a message

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse Twilio node documentation integration templates](https://n8n.io/integrations/twilio) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [Twilio's documentation](https://www.twilio.com/docs/usage/api) for more information about the service.

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/custom-api-actions-for-existing-nodes) for more information.
