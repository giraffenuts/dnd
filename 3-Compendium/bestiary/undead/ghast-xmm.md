---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Ghast"]
---
# [Ghast](3-Compendium\bestiary\undead/ghast-xmm.md)
*Source: Monster Manual (2024) p. 130*  

Ghasts frequently organize ghouls into packs to despoil crypts and steal the wealth within.

## Ghasts

*Tyrants among Corpses*

- **Habitat.** Swamp, Underdark, Urban  
- **Treasure.** Any  

Ghasts are reeking, undying corpses closely related to ghouls. They hunger for the vices they enjoyed in life as much as they do for rotting flesh.

```statblock
"name": "Ghast (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "36"
"hit_dice": "8d8"
"stats":
- !!int "16"
- !!int "17"
- !!int "10"
- !!int "11"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Compendium/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "Constitution Saving Throw: DC 10, any creature that starts its turn in\
    \ a 5-foot [Emanation [Area of Effect]](3-Compendium/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from the ghast. Failure: The target has the [Poisoned](3-Compendium/rules/conditions.md#Poisoned)\
    \ condition until the start of its next turn. Success: The target is immune\
    \ to this ghast's Stench for 24 hours."
  "name": "Stench"
"actions":
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 7 (1d8 + 3) Piercing damage plus\
    \ 9 (2d8) Necrotic damage."
  "name": "Bite"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 10 (2d6 + 3) Slashing damage. If\
    \ the target is a non-Undead creature, it is subjected to the following effect.\
    \ Constitution Saving Throw: DC 10. Failure: The target has the [Paralyzed](3-Compendium/rules/conditions.md#Paralyzed)\
    \ condition until the end of its next turn."
  "name": "Claw"
"source":
- "XMM"
```
^statblock

## Environment

swamp, underdark, urban