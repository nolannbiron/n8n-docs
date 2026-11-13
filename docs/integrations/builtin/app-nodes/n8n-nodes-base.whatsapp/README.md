---
title: WhatsApp Business Cloud node documentation
description: >-
  Learn how to use the WhatsApp Business Cloud node in n8n. Follow technical
  documentation to integrate WhatsApp Business Cloud node into your workflows.
contentType:
  - integration
  - reference
priority: high
nodeTitle: n8n-nodes-base.whatsapp
originalFilePath: integrations/builtin/app-nodes/n8n-nodes-base.whatsapp/index.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.whatsapp'
url: 'https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.whatsapp'
layout:
  description:
    visible: false
---

# WhatsApp Business Cloud node <a href="#whatsapp-business-cloud-node" id="whatsapp-business-cloud-node"></a>

Use the WhatsApp Business Cloud node to automate work in WhatsApp Business, and integrate WhatsApp Business with other applications. n8n has built-in support for a wide range of WhatsApp Business features, including sending messages, and uploading, downloading, and deleting media. 

On this page, you'll find a list of operations the WhatsApp Business Cloud node supports and links to more resources.

{% hint style="info" %}
**Credentials**

Refer to [WhatsApp Business Cloud credentials](../../credentials/whatsapp.md) for guidance on setting up authentication.
{% endhint %}

{% hint style="info" %}
**Human-in-the-loop for AI tool calls**

This node can be used as a human review step for AI Agent tool calls. When configured this way, the AI Agent will pause and request human approval through this service before executing tools that require oversight. Learn more in [Human-in-the-loop for AI tool calls](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/ai-examples/human-in-the-loop-for-tools).
{% endhint %}

## Operations <a href="#operations" id="operations"></a>

* Message
	* Send
	* Send and Wait for Response
	* Send Template
* Media
	* Upload
	* Download
	* Delete

## Waiting for a response <a href="#waiting-for-a-response" id="waiting-for-a-response"></a>

By choosing the **Send and Wait for a Response** operation, you can send a message and pause the workflow execution until a person confirms the action or provides more information.

### Response Type <a href="#response-type" id="response-type"></a>

You can choose between the following types of waiting and approval actions:

* **Approval**: Users can approve or disapprove from within the message.
* **Free Text**: Users can submit a response with a form.
* **Custom Form**: Users can submit a response with a custom form.

You can customize the waiting and response behavior depending on which response type you choose. You can configure these options in any of the above response types:

* **Limit Wait Time**: Whether the workflow will automatically resume execution after a specified time limit. This can be an interval or a specific wall time.
* **Append n8n Attribution**: Whether to mention in the message that it was sent automatically with n8n (turned on) or not (turned off).

### Approval response customization <a href="#approval-response-customization" id="approval-response-customization"></a>

When using the Approval response type, you can choose whether to present only an approval button or both approval *and* disapproval buttons.

You can also customize the button labels for the buttons you include.

### Free Text response customization <a href="#free-text-response-customization" id="free-text-response-customization"></a>

When using the Free Text response type, you can customize the message button label, the form title and description, and the response button label.

### Custom Form response customization <a href="#custom-form-response-customization" id="custom-form-response-customization"></a>

When using the Custom Form response type, you build a form using the fields and options you want.

You can customize each form element with the settings outlined in the [n8n Form trigger's form elements](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.formtrigger#form-elements). To add more fields, select the **Add Form Element** button.

You'll also be able to customize the message button label, the form title and description, and the response button label.

## Templates and examples <a href="#templates-and-examples" id="templates-and-examples"></a>


[Browse WhatsApp Business Cloud integration templates](https://n8n.io/integrations/whatsapp-business-cloud) or [search all templates](https://n8n.io/workflows/)

## Related resources <a href="#related-resources" id="related-resources"></a>

Refer to [WhatsApp Business Platform's Cloud API documentation](https://developers.facebook.com/docs/whatsapp/cloud-api) for details about the operations.

## Common issues <a href="#common-issues" id="common-issues"></a>

For common errors or issues and suggested resolution steps, refer to [Common Issues](common-issues.md).

## What to do if your operation isn't supported <a href="#what-to-do-if-your-operation-isnt-supported" id="what-to-do-if-your-operation-isnt-supported"></a>

If this node doesn't support the operation you want to do, you can use the [HTTP Request node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) to call the service's API.

You can use the credential you created for this service in the HTTP Request node: 

1. In the HTTP Request node, select **Authentication** > **Predefined Credential Type**.
1. Select the service you want to connect to.
1. Select your credential.

Refer to [Custom API operations](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/custom-api-actions-for-existing-nodes) for more information.
