---
obsidianUIMode: preview
cssclasses: json5e-hazard
tags:
- ttrpg-cli/compendium/src/5e/xdmg
- ttrpg-cli/hazard/trp
aliases: ["Poisoned Needle"]
---
# Poisoned Needle
*Generic Hazard*  

A poisoned needle is hidden in a lock. When a creature opens the lock with any object other than the proper key, the needle springs out and stabs the creature. The creature makes a DC 11 Constitution saving throw. On a failed save, the creature takes `dice:1d10|noform|avg|text(5)` (`1d10`) Poison damage and has the [Poisoned](3-Compendium/rules/conditions.md#Poisoned) condition for 1 hour. On a successful save, the creature takes half as much damage only.

## Avoid

The trap doesn't trigger if the lock is opened using a [Knock](3-Compendium/spells/knock-xphb.md) spell or similar magic.

## Detect and Disarm

As a [Search](3-Compendium/rules/actions.md#Search) action, a creature can examine the trapped lock and make a DC 15 Wisdom ([Perception](3-Compendium/rules/skills.md#Perception)) check, detecting the needle on a successful check. Once the trap is detected, a character can take an action to try to disarm the trap, doing so with a successful DC 15 Dexterity ([Sleight of Hand](3-Compendium/rules/skills.md#Sleight%20of%20Hand)) check. On a failed check, the creature triggers the trap.

## At Higher Levels

You can scale the trap for higher levels by increasing the damage and the save DC, as shown in the following table.

| Levels | Poison Damage | Save DC |
|--------|---------------|---------|
| 5–10 | 11 (`dice:2d10\|noform\|avg` (`2d10`)) | 13 |
| 11–16 | 22 (`dice:4d10\|noform\|avg` (`4d10`)) | 15 |
| 17–20 | 55 (`dice:10d10\|noform\|avg` (`10d10`)) | 17 |
^levels-poison-damage-save-dc

*Source: Dungeon Master's Guide (2024) p. 102*