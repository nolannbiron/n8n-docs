---
description: >-
  n8n provides these methods to make it easier to perform common tasks in the
  LangChain Code node.
contentType: reference
hide:
  - toc
nodeTitle: LangChain Code node
originalFilePath: code/builtin/langchain-methods.md
originalUrl: 'https://docs.n8n.io/code/builtin/langchain-methods'
url: >-
  https://docs.n8n.io/build/code-in-n8n/use-built-in-shortcuts/langchain-code-node
layout:
  description:
    visible: false
---
# LangChain Code node methods <a href="#langchain-code-node-methods" id="langchain-code-node-methods"></a>

n8n provides these methods to make it easier to perform common tasks in the [LangChain Code node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.code).

{% hint style="info" %}
**LangChain Code node only**

The built-in methods and variables on this page are for use in expressions in the LangChain Code node. You can't use them in other nodes.
{% endhint %}

| Method | Description |
| ------ | ----------- |
| `this.addInputData(inputName, data)` | Populate the data of a specified non-main input. Useful for mocking data.<ul><li>`inputName` is the input connection type, and must be one of: `ai_agent`, `ai_chain`, `ai_document`, `ai_embedding`, `ai_languageModel`, `ai_memory`, `ai_outputParser`, `ai_retriever`, `ai_textSplitter`, `ai_tool`, `ai_vectorRetriever`, `ai_vectorStore`</li><li>`data` contains the data you want to add. Refer to [Data structure](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/work-with-data/understand-n8ns-data-structure) for information on the data structure expected by n8n.</li></ul> |
| `this.addOutputData(outputName, data)` | Populate the data of a specified non-main output. Useful for mocking data.<ul><li>`outputName` is the input connection type, and must be one of: `ai_agent`, `ai_chain`, `ai_document`, `ai_embedding`, `ai_languageModel`, `ai_memory`, `ai_outputParser`, `ai_retriever`, `ai_textSplitter`, `ai_tool`, `ai_vectorRetriever`, `ai_vectorStore`</li><li>`data` contains the data you want to add. Refer to [Data structure](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/work-with-data/understand-n8ns-data-structure) for information on the data structure expected by n8n.</li></ul> |
| `this.getInputConnectionData(inputName, itemIndex, inputIndex?)` | Get data from a specified non-main input.<ul><li>`inputName` is the input connection type, and must be one of: `ai_agent`, `ai_chain`, `ai_document`, `ai_embedding`, `ai_languageModel`, `ai_memory`, `ai_outputParser`, `ai_retriever`, `ai_textSplitter`, `ai_tool`, `ai_vectorRetriever`, `ai_vectorStore`</li><li>`itemIndex` should always be `0` (this parameter will be used in upcoming functionality)</li><li>Use `inputIndex` if there is more than one node connected to the specified input.</li></ul> |
| `this.getInputData(inputIndex?, inputName?)` | Get data from the main input. |
| `this.getNode()` | Get the current node. |
| `this.getNodeOutputs()` | Get the outputs of the current node. |
| `this.getExecutionCancelSignal()` | Use this to stop the execution of a function when the workflow stops. n8n handles this in most workflows, but you may need it if you build your own chains or agents. |

## Related resources

* [Use built-in shortcuts](../use-built-in-shortcuts.md)
* [JMESPath](jmespath.md)
* [HTTP node](http-node.md)
* [n8n metadata](n8n-metadata.md)
