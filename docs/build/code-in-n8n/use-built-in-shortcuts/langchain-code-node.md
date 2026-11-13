---
contentType: reference
hide:
  - toc
nodeTitle: LangChain Code node
originalFilePath: code/builtin/langchain-methods.md
originalUrl: https://docs.n8n.io/code/builtin/langchain-methods
url: >-
  https://docs.n8n.io/build/code-in-n8n/use-built-in-shortcuts/langchain-code-node
description: >-
  n8n provides these methods to make it easier to perform common tasks in the
  LangChain Code node.
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

# LangChain Code node

n8n provides these methods to make it easier to perform common tasks in the [LangChain Code node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.code).

{% hint style="info" %}
**LangChain Code node only**

The built-in methods and variables on this page are for use in expressions in the LangChain Code node. You can't use them in other nodes.
{% endhint %}

| Method                                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `this.addInputData(inputName, data)`                             | <p>Populate the data of a specified non-main input. Useful for mocking data.</p><ul><li><code>inputName</code> is the input connection type, and must be one of: <code>ai_agent</code>, <code>ai_chain</code>, <code>ai_document</code>, <code>ai_embedding</code>, <code>ai_languageModel</code>, <code>ai_memory</code>, <code>ai_outputParser</code>, <code>ai_retriever</code>, <code>ai_textSplitter</code>, <code>ai_tool</code>, <code>ai_vectorRetriever</code>, <code>ai_vectorStore</code></li><li><code>data</code> contains the data you want to add. Refer to <a href="../../work-with-data/understand-n8ns-data-structure.md">Data structure</a> for information on the data structure expected by n8n.</li></ul>   |
| `this.addOutputData(outputName, data)`                           | <p>Populate the data of a specified non-main output. Useful for mocking data.</p><ul><li><code>outputName</code> is the input connection type, and must be one of: <code>ai_agent</code>, <code>ai_chain</code>, <code>ai_document</code>, <code>ai_embedding</code>, <code>ai_languageModel</code>, <code>ai_memory</code>, <code>ai_outputParser</code>, <code>ai_retriever</code>, <code>ai_textSplitter</code>, <code>ai_tool</code>, <code>ai_vectorRetriever</code>, <code>ai_vectorStore</code></li><li><code>data</code> contains the data you want to add. Refer to <a href="../../work-with-data/understand-n8ns-data-structure.md">Data structure</a> for information on the data structure expected by n8n.</li></ul> |
| `this.getInputConnectionData(inputName, itemIndex, inputIndex?)` | <p>Get data from a specified non-main input.</p><ul><li><code>inputName</code> is the input connection type, and must be one of: <code>ai_agent</code>, <code>ai_chain</code>, <code>ai_document</code>, <code>ai_embedding</code>, <code>ai_languageModel</code>, <code>ai_memory</code>, <code>ai_outputParser</code>, <code>ai_retriever</code>, <code>ai_textSplitter</code>, <code>ai_tool</code>, <code>ai_vectorRetriever</code>, <code>ai_vectorStore</code></li><li><code>itemIndex</code> should always be <code>0</code> (this parameter will be used in upcoming functionality)</li><li>Use <code>inputIndex</code> if there is more than one node connected to the specified input.</li></ul>                        |
| `this.getInputData(inputIndex?, inputName?)`                     | Get data from the main input.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `this.getNode()`                                                 | Get the current node.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| `this.getNodeOutputs()`                                          | Get the outputs of the current node.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `this.getExecutionCancelSignal()`                                | Use this to stop the execution of a function when the workflow stops. n8n handles this in most workflows, but you may need it if you build your own chains or agents.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

## Related resources

* [Use built-in shortcuts](./)
* [JMESPath](jmespath.md)
* [HTTP node](http-node.md)
* [n8n metadata](n8n-metadata.md)
