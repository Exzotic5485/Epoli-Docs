---
title: Damage Limit (Power Type)
date: 22-05-2022
---
# Damage Limit
_Power Type_

Makes the player unable to take more than the specified damage limit, accepts a damage condition.

Type ID: `epoli:damage_limit`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`limit` | [Float](float.md) | | The amount of damage to limit to (2 = 1 heart)
`damage_condition` | [Damage Condition Type](https://origins.readthedocs.io/en/latest/types/damage_condition_types/#damage_condition_types) | _optional_ | If specified, the limit will only apply to that condition.

### Examples

```json
{
	"type": "epoli:damage_limit",
	"limit": 2,
	"damage_condition": {
		"type": "origins:attacker",
		"entity_condition": {
			"type": "origins:entity_type",
			"entity_type": "minecraft:zombie"
		}
	}
}
```
This example will limit your damage taken from a zombie to a max of 2.
