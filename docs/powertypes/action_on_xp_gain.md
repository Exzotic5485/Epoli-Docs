---
title: Action On XP Gain (Power Type)
date: 22-04-2022
---
# Action On XP Gain
_Power Type_

Executes an [Entity Action Type](https://origins.readthedocs.io/en/latest/types/entity_action_types/) when the player gains experience.

Type ID: `epoli:action_on_xp_gain`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`entity_action` | [Entity Action Type](https://origins.readthedocs.io/en/latest/types/entity_action_types/) | | The action to execute on the player.


### Examples

```json
{
    "type": "epoli:action_on_xp_gain",
    "entity_action": {
        "type": "origins:execute_command",
        "command": "say Gained XP :)"
    }
}
```
This example will execute the command `Say Gained XP :)` on the player when they gain experience.
