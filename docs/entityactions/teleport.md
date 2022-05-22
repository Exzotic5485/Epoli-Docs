---
title: Teleport (Entity Action Type)
date: 22-04-2022
---
# Teleport
_Entity Action Type_

This is used to teleport without having to use `apoli:execute_command`.

Type ID: `epoli:teleport`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`x` | [Double](double.md) |  | The X coordinate.
`y` | [Double](double.md) |  | The y coordinate.
`z` | [Double](double.md) |  | The z coordinate.
`dimension` | [String](string.md) |  | The dimension you wish to teleport to, use `current` for the dimension the entity is in.


### Examples

```json
"entity_action": {
	"type": "epoli:teleport",
	"x": 10,
    "y": 11,
    "z": 50,
    "dimension": "minecraft:overworld"
}
```
This example will teleport the entity to 10, 11, 50 in the overworld.
