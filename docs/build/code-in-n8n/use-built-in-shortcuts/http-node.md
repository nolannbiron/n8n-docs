---
description: >-
  n8n provides these methods to make it easier to perform common tasks in
  expressions.
contentType: reference
hide:
  - toc
nodeTitle: HTTP node
originalFilePath: code/builtin/http-node-variables.md
originalUrl: 'https://docs.n8n.io/code/builtin/http-node-variables'
url: 'https://docs.n8n.io/build/code-in-n8n/use-built-in-shortcuts/http-node'
layout:
  description:
    visible: false
---

# HTTP node variables <a href="#http-node-variables" id="http-node-variables"></a>

Variables for working with HTTP node requests and responses when using pagination.

Refer to [HTTP Request](https://app.gitbook.com/s/BKcbOzIWja8NfqKDcqHc/builtin/core-nodes/n8n-nodes-base.httprequest) for guidance on using the HTTP node, including configuring pagination.

Refer to [HTTP Request node cookbook | Pagination](../cookbook/http-request-node/pagination.md) for example pagination configurations.

{% hint style="info" %}
**HTTP node only**

These variables are for use in expressions in the HTTP node. You can't use them in other nodes.
{% endhint %}
| Variable | Description |
| -------- | ----------- |
| `$pageCount` | The pagination count. Tracks how many pages the node has fetched. |
| `$request` | The request object sent by the HTTP node. |
| `$response` | The response object from the HTTP call. Includes `$response.body`, `$response.headers`, and `$response.statusCode`. The contents of `body` and `headers` depend on the data sent by the API. |

## Related resources

* [Use built-in shortcuts](../use-built-in-shortcuts.md)
* [JMESPath](jmespath.md)
* [LangChain Code node](langchain-code-node.md)
* [n8n metadata](n8n-metadata.md)
