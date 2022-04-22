---
title: Redstone (Power Type)
date: 22-04-2022
---
# Redstone
_Power Type_

This will power redstone components the player is standing on and deactivate once moving off it.

Type ID: `epoli:redstone`


### Fields
_None._


### Examples

```json
{
	"type": "epoli:redstone",
	"strength": 5,
	"condition": {
		"type": "origins:sneaking"
	}
}
```
This example will activate the redstone component as long as the player is sneaking.
