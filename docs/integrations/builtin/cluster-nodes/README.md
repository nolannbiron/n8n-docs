---
contentType: overview
title: Cluster nodes
description: 'Understand cluster nodes in n8n, and browse the cluster nodes library.'
nodeTitle: Cluster nodes
originalFilePath: integrations/builtin/cluster-nodes/index.md
originalUrl: 'https://docs.n8n.io/integrations/builtin/cluster-nodes'
url: 'https://docs.n8n.io/integrations/builtin/cluster-nodes'
layout:
  description:
    visible: false
---

# Cluster nodes <a href="#cluster-nodes" id="cluster-nodes"></a>

[Cluster nodes](https://app.gitbook.com/s/F723O5csUOHtKMrXjQzT/key-concept-glossary#cluster-node-n8n) are node groups that work together to provide functionality in an n8n workflow. Instead of using a single node, you use a [root node](https://app.gitbook.com/s/F723O5csUOHtKMrXjQzT/key-concept-glossary#root-node-n8n) and one or more [sub-nodes](https://app.gitbook.com/s/F723O5csUOHtKMrXjQzT/key-concept-glossary#sub-node-n8n) that extend the functionality of the node.

![A workflow diagram with one root node connected to two sub-nodes](../../../../assets/root-sub-nodes.png)


## Root nodes <a href="#root-nodes" id="root-nodes"></a>

Each cluster starts with one [root node](#user-content-fn-1)[^1].

## Sub-nodes <a href="#sub-nodes" id="sub-nodes"></a>

Each root node can have one or more sub-nodes[^2] attached to it.

[^1]: Each n8n cluster node contains a single root node that defines the main functionality of the cluster. One or more sub-nodes attach to the root node to extend its functionality.
[^2]: n8n cluster nodes consist of one or more sub-nodes connected to a root node. Sub-nodes extend the functionality of the root node, providing access to specific services or resources or offering specific types of dedicated processing, like calculator functionality, for example.
