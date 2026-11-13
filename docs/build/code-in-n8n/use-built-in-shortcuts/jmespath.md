---
contentType: reference
hide:
  - toc
nodeTitle: JMESPath
originalFilePath: code/builtin/jmespath.md
originalUrl: https://docs.n8n.io/code/builtin/jmespath
url: https://docs.n8n.io/build/code-in-n8n/use-built-in-shortcuts/jmespath
description: A method for working with the JMESPath library in n8n.
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
---

# JMESPath

This is an n8n-provided method for working with the [JMESPath](../../work-with-data/handle-special-data-types/query-json-data.md) library.

{% hint style="info" %}
**JavaScript only**

The Python Code node doesn't provide this method. To query JSON in Python, use standard Python instead. Refer to [Query JSON with JMESPath](../../work-with-data/handle-special-data-types/query-json-data.md) for a Python version of each example.
{% endhint %}

| Method        | Description                                       | Available in Code node? |
| ------------- | ------------------------------------------------- | :---------------------: |
| `$jmespath()` | Perform a search on a JSON object using JMESPath. |            ✅            |

## Related resources

* [Use built-in shortcuts](./)
* [HTTP node](http-node.md)
* [LangChain Code node](langchain-code-node.md)
* [n8n metadata](n8n-metadata.md)
