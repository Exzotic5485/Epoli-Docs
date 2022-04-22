# Epoli Documentation
This is the documentation/usage guide for Epoli an Apoli addon to help with origin creation.

[**Epoli Download**](https://www.curseforge.com/minecraft/mc-mods/epoli)

## Power Types
Unless stated otherwise, each power type supports a `condition` field that can check for [Entity Condition Types](https://origins.readthedocs.io/en/latest/types/entity_condition_types/). See [Power JSON](https://origins.readthedocs.io/en/latest/json/power/) for more details.

**List Of Power Types:**

* [Redstone](powertypes/redstone.md)
* [Prevent Soulsand Slowness](powertypes/prevent_soulsand_slowness.md)

## Entity Actions
Entity Action Types operate on an Entity. These are available to power/action types that provides an `entity_action` object field.

**List Of Power Types:**

* [Teleport To Spawn](entityactions/teleport_to_spawn.md)
* [Teleport](entityactions/teleport.md)
* [Save Location](entityactions/save_location.md)
* [Teleport Location](entityactions/teleport_location.md)