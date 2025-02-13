---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Giant Toad"]
---
# [Giant Toad](3-Compendium\bestiary\beast/giant-toad-xmm.md)
*Source: Monster Manual (2024) p. 360*  

```statblock
"name": "Giant Toad (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"stats":
- !!int "15"
- !!int "13"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
- "desc": "The toad can breathe air and water."
  "name": "Amphibious"
- "desc": "The toad's [Long Jump](3-Compendium/rules/variant-rules/long-jump-xphb.md)\
    \ is up to 20 feet and its [High Jump](3-Compendium/rules/variant-rules/high-jump-xphb.md)\
    \ is up to 10 feet with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 5 (1d6 + 2) Piercing damage plus\
    \ 5 (2d4) Poison damage. If the target is a Medium or smaller creature, it has\
    \ the [Grappled](3-Compendium/rules/conditions.md#Grappled) condition (escape\
    \ DC 12)."
  "name": "Bite"
- "desc": "The toad swallows a Medium or smaller target it is grappling. While swallowed,\
    \ the target isn't [Grappled](3-Compendium/rules/conditions.md#Grappled) but has\
    \ the [Blinded](3-Compendium/rules/conditions.md#Blinded) and [Restrained](3-Compendium/rules/conditions.md#Restrained)\
    \ conditions, and it has [Cover](3-Compendium/rules/variant-rules/cover-xphb.md)\
    \ against attacks and other effects outside the toad. In addition, the target\
    \ takes 10 (3d6) Acid damage at the end of each of the toad's turns. The toad\
    \ can have only one target swallowed at a time, and it can't use Bite while it\
    \ has a swallowed target. If the toad dies, a swallowed creature is no longer\
    \ [Restrained](3-Compendium/rules/conditions.md#Restrained) and can escape from\
    \ the corpse using 5 feet of movement, exiting with the [Prone](3-Compendium/rules/conditions.md#Prone)\
    \ condition."
  "name": "Swallow"
"source":
- "XMM"
```
^statblock

## Environment

coastal, forest, swamp, underdark