---
contentType: explanation
nodeTitle: Custom API actions for existing nodes
originalFilePath: integrations/custom-operations.md
originalUrl: 'https://docs.n8n.io/integrations/custom-operations'
url: 'https://docs.n8n.io/integrations/builtin/custom-api-actions-for-existing-nodes'
layout:
  description:
    visible: false
---

# Custom API operations <a href="#custom-api-operations" id="custom-api-operations"></a>

One of the most complex parts of setting up API calls is managing authentication. n8n provides [credentials](https://app.gitbook.com/s/CxSeOtVxqqhfxMSac0AV/key-concept-glossary#credential-n8n) support for operations and services beyond those supported by built-in nodes.

* Custom operations for existing nodes: n8n supplies hundreds of nodes to create workflows that link multiple products. However, some nodes don't include all the possible operations supported by a product's API. You can work around this by making a custom API call using the [HTTP Request](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) node.
* Credential-only nodes: n8n includes credential-only nodes. These are integrations where n8n supports setting up credentials for use in the HTTP Request node, but doesn't provide a standalone node. You can find a credential-only node in the nodes panel, as you would for any other integration.

## Predefined credential types <a href="#predefined-credential-types" id="predefined-credential-types"></a>

A predefined credential type is a credential that already exists in n8n. You can use predefined credential types instead of generic credentials in the HTTP Request and GraphQL nodes.

For example: you create an Asana credential, for use with the Asana node. Later, you want to perform an operation that isn't supported by the Asana node, using Asana's API. You can use your existing Asana credential in the HTTP Request node to perform the operation, without additional authentication setup.

### Using predefined credential types <a href="#using-predefined-credential-types" id="using-predefined-credential-types"></a>

To use a predefined credential type:

1. Open your HTTP Request or GraphQL node, or add a new one to your workflow.
2. In **Authentication**, select **Predefined Credential Type**.
3. In **Credential Type**, select the API you want to use. 
4. In **Credential for `<API name>`**, you can:
    1. Select an existing credential for that platform, if available.
    2. Select **Create New** to create a new credential.


### Credential scopes <a href="#credential-scopes" id="credential-scopes"></a>

Some existing credential types have specific scopes: the parts of the API they can access. n8n warns you about this when you select the credential type.

For example, follow the steps in [Using predefined credential types](#using-predefined-credential-types), and select **Google Calendar OAuth2 API** as your **Credential Type**. n8n displays a box listing the two scopes this credential type covers: `calendar` and `calendar.events`.

![Scopes notice for the Google Calendar OAuth2 API credential type](../.gitbook/assets/scopes.png)

