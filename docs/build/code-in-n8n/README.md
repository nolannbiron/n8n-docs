---
title: Code in n8n Documentation and Guides
contentType: overview
hide:
  - feedback
  - kapaButton
nodeTitle: Code in n8n
originalFilePath: code/index.md
originalUrl: https://docs.n8n.io/code
url: https://docs.n8n.io/build/
description: >-
  Access documentation and guides on using code and expressions in n8n and other
  developer resources.
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

# Code in n8n

n8n is a low-code tool. This means you can do a lot without code, then add code when needed.

## In this section

* [Using the Code node](using-the-code-node.md): add JavaScript or Python code to your workflow.
* [Get coding help from AI](get-coding-help-from-ai.md): use GPT to generate code in the Code node.
* [Use built-in shortcuts](use-built-in-shortcuts/): reference for n8n's built-in methods and variables for use in expressions and code.
* [Define custom variables](define-custom-variables.md): store and reuse values across your workflows.
* [Cookbook](cookbook/): examples and recipes for common coding tasks.

## Code in your workflows <a href="#code-in-your-workflows" id="code-in-your-workflows"></a>

There are two places in your workflows where you can use code:

*   **Expressions**

    Use expressions[^1] to transform [data](../work-with-data/) in your nodes. You can use JavaScript in expressions, as well as n8n's [Built-in methods and variables](use-built-in-shortcuts/).

    [→ Expressions](../work-with-data/expressions-versus-data-nodes.md)
*   **Code node**

    Use the Code node to add JavaScript or Python to your workflow.

    [→ Code node](using-the-code-node.md)

## Other technical resources <a href="#other-technical-resources" id="other-technical-resources"></a>

These are features that are relevant to technical users.

### Technical nodes <a href="#technical-nodes" id="technical-nodes"></a>

n8n provides core nodes, which simplify adding key functionality such as API requests, webhooks, scheduling, and file handling.

*   **Write a backend**

    The [HTTP Request](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest), [Webhook](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.webhook), and [Code](using-the-code-node.md) nodes help you make API calls, respond to webhooks, and write any JavaScript in your workflow.

    Use this do things like [Create an API endpoint](https://n8n.io/workflows/1750-creating-an-api-endpoint/).

    [→ Core nodes](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes)
*   **Represent complex logic**

    You can build complex flows, using nodes like [If](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.if), [Switch](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.switch), and [Merge](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.merge) nodes.

    [→ Flow logic](../flow-logic/)

### Other developer resources <a href="#other-developer-resources" id="other-developer-resources"></a>

*   **The n8n API**

    n8n provides an API, where you can programmatically perform many of the same tasks as you can in the GUI. There's an [n8n API node](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.n8n) to access the API in your workflows.

    [→ API](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/n8n-api)
*   **Self-host**

    You can self-host n8n. This keeps your data on your own infrastructure.

    [→ Hosting](https://app.gitbook.com/s/CVqOCDXNeshWSm0VR543/host-n8n)
*   **Build your own nodes**

    You can build custom nodes, install them on your n8n instance, and publish them to [npm](https://www.npmjs.com/).

    [→ Creating nodes](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/create-nodes/overview)

## Related resources

* [Build](../)
* [Understand workflows](../understand-workflows/)
* [Build and manage agents](../build-and-manage-agents/)
* [Ways of building workflows](../ways-of-building-workflows/)
* [Manage workflows](../manage-workflows/)
* [Flow logic](../flow-logic/)
* [Work with data](../work-with-data/)
* [Integrate AI](../integrate-ai/)
* [Keyboard shortcuts](../keyboard-shortcuts.md)

[^1]: In n8n, expressions allow you to populate node parameters dynamically by executing JavaScript code. Instead of providing a static value, you can use the n8n expression syntax to define the value using data from previous nodes, other workflows, or your n8n environment.
