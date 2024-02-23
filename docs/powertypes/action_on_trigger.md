---
title: Action On Trigger (Power Type)
date: 22-04-2022
---
# Action On Trigger
_Power Type_

Executes an [Entity Action Type](https://origins.readthedocs.io/en/latest/types/entity_action_types/) when the player uses the `/trigger` command.

Type ID: `epoli:action_on_trigger`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`entity_action` | [Entity Action Type](https://origins.readthedocs.io/en/latest/types/entity_action_types/) | | The action to execute on the player.
`objective` | [String](string.md) | | The name of the scoreboard that triggers
`operation` | [Array](https://origins.readthedocs.io/en/latest/types/data_types/array/) of [Strings](https://origins.readthedocs.io/en/latest/types/data_types/string/) | | Which type of trigger to activate the entity action for. Accepts: `"add"`, `"set"`, `"simple"`.
`comparison` | [Comparison](comparison.md) | `">="` | How the value of the power that will be evaluated should be compared to the specified value.
`compare_to` | [Integer](integer.md) | `0` | The value to compare the value of the power that will be evaluated to.


### Examples

```json
{
    "type": "epoli:action_on_trigger",
    "entity_action": {
        "type": "origins:execute_command",
        "command": "say Triggered :)"
    },
	"objective": "origintrigger",
	"operation": ["add", "set"],
    "comparison": ">=",
    "compare_to": 5
}
```
This example will execute the command `Triggered :)` on the player when they use the trigger command for the objective `origintrigger` and using either `add` or `set` with a value of `5` or above.
