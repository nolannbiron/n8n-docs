---
contentType: overview
title: Advanced AI examples and concepts
hide:
  - toc
nodeTitle: AI examples
originalFilePath: advanced-ai/examples/introduction.md
originalUrl: https://docs.n8n.io/advanced-ai/examples/introduction
url: https://docs.n8n.io/build/integrate-ai/ai-examples
description: Example workflows and use cases for building AI functionality using n8n.
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

# AI examples

This section provides explanations of important AI concepts, and workflow templates that highlight those concepts, with explanations and configuration guides. The examples cover common use cases and highlight different features of advanced AI in n8n.

*   **Agents and chains**

    Learn about agents[^1] and chains[^2] in AI, including exploring key differences using the example workflow.

    [→ What's a chain in AI?](../understand-ai-components/what-chains-do.md)\
    [→ What's an agent in AI?](../understand-ai-components/what-agents-do.md)\
    [→ Demonstration of key differences between agents and chains](../understand-ai-components/agents-vs-chains.md)
*   **Call n8n Workflow Tool**

    Learn about tools[^3] in AI, then explore examples that use n8n workflows as custom tools to give your AI workflow access to more data.

    [→ What's a tool in AI?](../understand-ai-components/how-tools-work.md)\
    [→ Chat with Google Sheets](use-google-sheets-as-a-data-source.md)\
    [→ Call an API to fetch data](call-apis.md)\
    [→ Set up a human fallback](set-a-human-fallback-for-ai-workflows.md)\
    [→ Let AI specify tool parameters with `$fromAI()`](use-ai-for-parameters.md)
*   **Vector databases**

    Learn about [vector databases](#user-content-fn-4)[^4] in AI, along with related concepts including embeddings[^5] and retrievers.

    [→ What's a vector database?](../understand-ai-components/store-and-search-data-with-vectors.md)\
    [→ Populate a Pinecone vector database from a website](use-website-content.md)
*   **Memory**

    Learn about memory[^6] in AI.

    [→ What's memory in AI?](../understand-ai-components/how-memory-works.md)
*   **AI workflow templates**

    You can browse AI templates, included community contributions, on the n8n website.

    [→ Browse all AI templates](https://n8n.io/workflows/?categories=25)

## In this section

* [Use Google Sheets as a data source](use-google-sheets-as-a-data-source.md): use the n8n workflow tool to load data from Google Sheets into your AI workflow.
* [Call APIs](call-apis.md): use the n8n workflow tool to load data from an API using the HTTP Request node.
* [Use website content](use-website-content.md): scrape a website, load the data into Pinecone, then query it in a chat workflow.
* [Human-in-the-loop for tools](human-in-the-loop-for-tools.md): require human approval before an AI Agent runs a tool.
* [Set a human fallback for AI workflows](set-a-human-fallback-for-ai-workflows.md): trigger a human answer when the AI can't help.
* [Use AI for parameters](use-ai-for-parameters.md): use `$fromAI()` to dynamically populate parameters for AI app tools.

## Related resources

* [Integrate AI](../)
* [MCP servers](../mcp-servers.md)
* [Understand AI components](../understand-ai-components/)
* [LangChain in n8n](../langchain-in-n8n.md)
* [Test and improve AI workflows](../test-and-improve-ai-workflows/)

[^1]: AI agents are artificial intelligence systems capable of responding to requests, making decisions, and performing real-world tasks for users. They use large language models (LLMs) to interpret user input and make decisions about how to best process requests using the information and resources they have available.

[^2]: AI chains allow you to interact with large language models (LLMs) and other resources in sequences of calls to components. AI chains in n8n don't use persistent memory, so you can't use them to reference previous context (use AI agents for this).

[^3]: In an AI context, a tool is an add-on resource that the AI can refer to for specific information or functionality when responding to a request. The AI model can use a tool to interact with external systems or complete specific, focused tasks.

[^4]: A vector store, or vector database, stores mathematical representations of information. Use with embeddings and retrievers to create a database that your AI can access when answering questions.

[^5]: Embeddings are numerical representations of data using vectors. They're used by AI to interpret complex data and relationships by mapping values across many dimensions. Vector databases, or vector stores, are databases designed to store and access embeddings.

[^6]: In an AI context, memory allows AI tools to persist message context across interactions. This allows you to have a continuing conversations with AI agents, for example, without submitting ongoing context with each message. In n8n, AI agent nodes can use memory, but AI chains can't.
