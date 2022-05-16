---
title: Action On Death (Power Type)
date: 22-04-2022
---
# Action On Death
_Power Type_

Executes an [Entity Action Type](https://origins.readthedocs.io/en/latest/types/entity_action_types/) when the player dies.

Type ID: `epoli:action_on_death`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`entity_action` | [Entity Action Type](https://origins.readthedocs.io/en/latest/types/entity_action_types/) | | The action to execute on the player.
`damage_condition` | [Damage Condition Type](https://origins.readthedocs.io/en/latest/types/damage_condition_types/) | _optional_ | If specified, the entity action will only be run if the condition passes.


### Examples

```json
{
	"type": "epoli:action_on_death",
	"entity_action": {
		"type": "origins:execute_command",
		"command": "say Deathed"
	},
	"damage_condition": {
		"type": "origins:amount",
		"comparison": ">=",
		"compare_to": 5
	}
}
```
This example will execute the command `say Deathed` on the player when they die and the attacker damage amount is `5` or above.
