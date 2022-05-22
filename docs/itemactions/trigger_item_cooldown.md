---
title: Trigger Item Cooldown (Item Action Type)
date: 22-05-2022
---
# Trigger Item Cooldown
_Item Action Type_

This triggers the cooldown of an item like an enderpearl, shield etc (Though this will work on any items, e.g. block will not allow you to place)

Type ID: `epoli:trigger_item_cooldown`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`duration` | [Int](int.md) | `20` | How long to trigger the cooldown for

### Examples

```json
"item_action": {
	"type": "epoli:trigger_item_cooldown",
	"duration": 20
}
```
This example will trigger an items cooldown for 20 ticks.