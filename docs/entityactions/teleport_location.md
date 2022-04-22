---
title: Teleport Location (Entity Action Type)
date: 22-04-2022
---
# Redstone
_Entity Action Type_

This will teleport the entity to the saved position from the entity action: [`epoli:save_location`](save_location.md)

Type ID: `epoli:teleportlocation`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`saveid` | [String](string.md) | | The same identifier used in `epoli:save_location`.


### Examples

```json
"entity_action": {
	"type": "epoli:teleport_location",
	"saveid": "myorigin_save"
}
```
This example will teleport the entity to the saved location "myorigin_save".
