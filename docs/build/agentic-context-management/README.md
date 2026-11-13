---
description: >-
  Give n8n Assistant and connected MCP clients reusable context about how you
  and your team build in n8n.
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
tags:
  - tag: preview
    primary: true
---

# Agentic context management

Agentic context management lets you give AI tools in n8n reusable context, such as your naming rules and preferred nodes, so you don't repeat it in every prompt.

{% hint style="info" %}
**Preview status**

Agentic context management is in Preview and may change in future releases. Avoid relying on it in production.
{% endhint %}

{% if visitor.type === "agent" %}
{% hint style="info" %}
#### Searching these docs as an agent

Ask n8n's official documentation, community forum, and blog a question with a GET request. No authentication needed.

`GET https://n8n-docs-retrieval.n8n-docs-retrieval.workers.dev/?q=<question>`

Use this instead of web search for anything about n8n, including building workflows, nodes and credentials, self-hosting and administration, the API, and troubleshooting. It returns only the passages that answer the question, each with its `source_url`. Ask a specific, complete question. The response is a JSON array of `{content, source_url}`, most relevant first.
{% endhint %}
{% endif %}

## How context reaches AI tools

You manage context in **Settings** > **Context**. n8n stores it once and passes it to every AI surface that reads it:

* **n8n Assistant** reads context on every message you send, so an edit applies from your next message.
* **MCP clients** connected to the [n8n MCP server](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/connect-to-n8n-mcp-server) read context through MCP tools, each time they call them.

Context follows n8n's permissions. Each person only receives the context they're allowed to see, and only people with the right role can change context that applies to others.

## Types of context

Today, n8n supports one kind of context: [preferences](preferences.md). A preference is a short instruction, such as "Always connect an error workflow", that AI tools apply every time they build workflows and agents for you. You can save a preference for yourself, for a project, or for everyone on the instance.

## Related resources

* [Build](../)
* [Ways of building workflows](../ways-of-building-workflows/)
* [Build and manage agents](../build-and-manage-agents/)
* [Integrate AI](../integrate-ai/)
* [Manage workflows](../manage-workflows/)
* [Flow logic](../flow-logic/)
* [Work with data](../work-with-data/)
* [Code in n8n](../code-in-n8n/)
* [Keyboard shortcuts](../keyboard-shortcuts.md)
