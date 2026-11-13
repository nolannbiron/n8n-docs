---
title: Nodes
contentType: overview
hide:
  - feedback
  - kapaButton
nodeTitle: Integrations
originalFilePath: integrations/index.md
originalUrl: https://docs.n8n.io/integrations
url: https://docs.n8n.io/integrations/
description: >-
  Learn about n8n's built-in nodes, community nodes, MCP servers, and generic
  integrations.
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
    visible: false
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Nodes

n8n calls integrations nodes.

Nodes are the building blocks of workflows in n8n. They're an entry point for retrieving data, a function to process data, or an exit for sending data. The data process includes filtering, recomposing, and changing data. There can be one or several nodes for your API, service or app. You can connect multiple nodes, which allows you to create complex workflows.

## Built-in nodes <a href="#built-in-nodes" id="built-in-nodes"></a>

n8n includes a collection of built-in integrations. Refer to [Built-in nodes](builtin/node-types.md) for documentation on all n8n's built-in nodes.

## Community nodes <a href="#community-nodes" id="community-nodes"></a>

As well as using the built-in nodes, you can also install community-built nodes. Refer to [Community nodes](community-nodes/installation-and-management/README.md) for more information.

## MCP servers <a href="#mcp-servers" id="mcp-servers"></a>

n8n also includes a registry of MCP servers you can connect to an agent directly from the node panel in one click. See [MCP servers](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/integrate-ai/mcp-servers/) for more information.

## Credential-only nodes and custom operations <a href="#credential-only-nodes-and-custom-operations" id="credential-only-nodes-and-custom-operations"></a>

One of the most complex parts of setting up API calls is managing authentication. n8n provides [credentials](https://app.gitbook.com/s/F723O5csUOHtKMrXjQzT/key-concept-glossary#credential-n8n) support for operations and services beyond those supported by built-in nodes.

* Custom operations for existing nodes: n8n supplies hundreds of nodes to create workflows that link multiple products. However, some nodes don't include all the possible operations supported by a product's API. You can work around this by making a custom API call using the [HTTP Request](https://app.gitbook.com/s/O1TZROfuy5oML7hdsuTl/builtin/core-nodes/n8n-nodes-base.httprequest) node.
* Credential-only nodes: n8n includes credential-only nodes. These are integrations where n8n supports setting up credentials for use in the HTTP Request node, but doesn't provide a standalone node. You can find a credential-only node in the nodes panel, as you would for any other integration.

Refer to [Custom operations](builtin/custom-api-actions-for-existing-nodes.md) for more information.

## Generic integrations <a href="#generic-integrations" id="generic-integrations"></a>

If you need to connect to a service where n8n doesn't have a node, or a credential-only node, you can still use the [HTTP Request](builtin/core-nodes/n8n-nodes-base.httprequest/README.md) node. Refer to the node page for details on how to set up authentication and create your API call.

## Where to go next <a href="#where-to-go-next" id="where-to-go-next"></a>

* If you want to create your own node, head over to the [Create nodes](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/create-nodes/overview) section.
* Check out [Community nodes](community-nodes/using-community-nodes.md) to learn about installing and managing community-built nodes.
* If you'd like to learn more about the different nodes in n8n, their functionalities and example usage, check out n8n's node libraries: [Core nodes](builtin/core-nodes/README.md), [Actions](builtin/app-nodes/README.md), and [Triggers](builtin/trigger-nodes/README.md).
* If you'd like to learn how to add the credentials for the different nodes, head over to the [Credentials](builtin/credentials/README.md) section.
