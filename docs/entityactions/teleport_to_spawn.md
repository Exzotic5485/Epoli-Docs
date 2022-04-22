---
title: Teleport To Spawn (Entity Action Type)
date: 22-04-2022
---
# Redstone
_Entity Action Type_

This will teleport the player back to the world spawn or their spawn point.

Type ID: `epoli:teleport_to_spawn`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`player_spawn` | [Boolean](boolean.md) | `false` | If it will teleport to the players spawn not world spawn.


### Examples

```json
"entity_action": {
	"type": "epoli:teleport_to_spawn",
	"player_spawn": false
}
```
This example will teleport the entity to the world spawn point.
