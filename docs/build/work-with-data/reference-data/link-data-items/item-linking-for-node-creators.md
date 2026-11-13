---
contentType: howto
nodeTitle: Item linking for node creators
originalFilePath: data/data-mapping/data-item-linking/item-linking-node-building.md
originalUrl: >-
  https://docs.n8n.io/data/data-mapping/data-item-linking/item-linking-node-building
url: >-
  https://docs.n8n.io/build/work-with-data/reference-data/link-data-items/item-linking-for-node-creators
layout:
  description:
    visible: false
---

# Item linking for node creators <a href="#item-linking-for-node-creators" id="item-linking-for-node-creators"></a>

{% hint style="info" %}
**Programmatic-style nodes only**

This guidance applies to programmatic-style nodes. If you're using declarative style, n8n handles paired items for you automatically.
{% endhint %}

Use n8n's item linking to access data from items that precede the current item. n8n needs to know which input item a given output item comes from. If this information is missing, expressions in other nodes may break. As a node developer, you must ensure any items returned by your node support this. 

This applies to programmatic nodes (including trigger nodes). You don't need to consider item linking when building a declarative-style node. Refer to [Choose your node building approach](https://app.gitbook.com/s/kEx4S6twxP979lboYaa8/create-nodes/plan-your-node/choose-a-node-building-style) for more information on node styles.

Start by reading [Item linking concepts](https://app.gitbook.com/s/BZpIXw3wFsNVcsJHaGPW/work-with-data/reference-data/link-data-items/how-items-link-through-workflows), which provides a conceptual overview of item linking, and details of the scenarios where n8n can handle the linking automatically.

If you need to handle item linking manually, do this by setting `pairedItem` on each item your node returns:

```typescript
// Use the pairedItem information of the incoming item
newItem = {
	"json": { . . . },
	"pairedItem": {
		"item": item.pairedItem,
		// Optional: choose the input to use
		// Set this if your node combines multiple inputs
		"input": 0
};

// Or set the index manually
newItem = {
		"json": { . . . }
		"pairedItem": {
			"item": i,
			// Optional: choose the input to use
			// Set this if your node combines multiple inputs
			"input": 0
		},
};
```

## Related resources

* [Link data items](./)
* [How items link through workflows](how-items-link-through-workflows.md)
* [Accessing linked items in the Code node](accessing-linked-items-in-the-code-node.md)
* [Preserving linking in the Code node](preserving-linking-in-the-code-node.md)
* [Item linking errors](item-linking-errors.md)
