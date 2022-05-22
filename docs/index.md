# Epoli Documentation
This is the documentation/usage guide for Epoli an Apoli addon to help with origin creation.

[**Epoli Download**](https://www.curseforge.com/minecraft/mc-mods/epoli)

## Power Types
Unless stated otherwise, each power type supports a `condition` field that can check for [Entity Condition Types](https://origins.readthedocs.io/en/latest/types/entity_condition_types/). See [Power JSON](https://origins.readthedocs.io/en/latest/json/power/) for more details.

**List Of Power Types:**

* [Redstone](powertypes/redstone.md)
* [Prevent Soulsand Slowness](powertypes/prevent_soulsand_slowness.md)
* [Action On Xp Gain](powertypes/action_on_xp_gain.md)
* [Action On Trigger](powertypes/action_on_trigger.md)
* [Passive](powertypes/passive.md)
* [Action On Death](powertypes/action_on_death.md)
* [Damage Limit](powertypes/damage_limit.md)
* [Multiply Bow Speed](powertypes/multiply_bow_speed.md)

## Entity Actions
Entity Action Types operate on an Entity. These are available to power/action types that provides an `entity_action` object field.

**List Of Entity Actions:**

* [Teleport To Spawn](entityactions/teleport_to_spawn.md)
* [Teleport](entityactions/teleport.md)
* [Save Location](entityactions/save_location.md)
* [Teleport Location](entityactions/teleport_location.md)
* [System Toast](entityactions/system_toast.md)

## Item Actions
Item Action Types operate on a stack of items. These are available to power/action types that provides an item_action object field.

**List Of Item Actions:**

* [Trigger Item Cooldown](itemactions/trigger_item_cooldown.md)