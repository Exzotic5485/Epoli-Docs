---
title: Passive (Power Type)
date: 22-04-2022
---
# Passive
_Power Type_

Mobs that match the entity condition will be passive towards the player.

Type ID: `epoli:passive`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`entity_condition` | [Entity Condition](https://origins.readthedocs.io/en/latest/types/entity_condition_types/) | | The condition of the mob.


### Examples

```json
{
    "type": "epoli:passive",
    "entity_condition": {
        "type": "origins:entity_type",
        "entity_type": "minecraft:zombie"
    }
}
```
This example will make all zombies passive to the player.
