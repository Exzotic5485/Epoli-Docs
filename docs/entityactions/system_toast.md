---
title: System Toast (Entity Action Type)
date: 22-05-2022
---
# System Toast
_Entity Action Type_

This is used to display a system toast / message at the top right of a players screen.

Type ID: `epoli:system_toast`


### Fields
Field  | Type | Default | Description
-------|------|---------|-------------
`title` | [String](string.md) |  | Displayed as the top/title of the toast (You can use a json text component)
`description` | [String](string.md) |  | Displayed as the bottom/main text of the toast (You can use a json text component)

### Examples

```json
"entity_action": {
	"type": "epoli:system_toast",
	"title": "Evolved",
    "description": "You have evolved"
}
```
This example will display a system toast to the player.