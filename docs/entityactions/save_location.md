---
title: Save Location (Entity Action Type)
date: 22-04-2022
---
# Redstone
_Entity Action Type_

This will save the entities current location/position to later use with [teleport location](teleport_location.md).

Type ID: `epoli:save_location`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`saveid` | [String](string.md) | | This must be a unique id and is an identifier for teleporting back to the saved location.
`overwrite` | [Boolean](boolean.md) | true | If false, if the player has already saved a location with that "saveid" it will not be overwritten.


### Examples

```json
"entity_action": {
	"type": "epoli:save_location",
	"saveid": "myorigin_save",
    "overwrite": true
}
```
This example will save the entities current location and overwrite any existing locations saved on the saveid "myorigin_save".
