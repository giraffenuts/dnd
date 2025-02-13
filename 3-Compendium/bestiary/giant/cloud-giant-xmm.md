---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Cloud Giant"]
---
# [Cloud Giant](3-Compendium\bestiary\giant/cloud-giant-xmm.md)
*Source: Monster Manual (2024) p. 74*  

## Cloud Giant

*Giant of the Loftiest Heights*

- **Habitat.** Mountain  
- **Treasure.** Arcana  

Cloud giants use the power of the skies to observe and subtly influence the world. These giants resemble humans with hair ranging from silver to blue and with skin in cloudlike shades from stark white to twilight hues. Curved canines grow in their upper jaws, extending past their lower lips. In battle, they attack with weapons wreathed in storm clouds and throw roaring thunderheads.

Most cloud giants inhabit citadels crowning tremendous mountains or magical palaces that drift amid the clouds. Many of these giants believe they possess similarly lofty status or purpose. Some view themselves as godlike beings who can manipulate and steal from terrestrial beings with impunity. Others claim their long lives and place among the clouds grant them unique perspectives, so they chronicle what they witness in the world below without interfering. In either case, cloud giants often possess fabulous magical treasures, either claimed from across the world or created by (and gigantically sized for) themselves.

```statblock
"name": "Cloud Giant (XMM)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "27"
- !!int "10"
- !!int "22"
- !!int "12"
- !!int "16"
- !!int "16"
"speed": "40 ft., fly 20 ft. (hover)"
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "11"
"senses": "passive Perception 21"
"languages": "Common, Giant"
"cr": "9"
"traits":
- "desc": "The giant casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Detect Magic](3-Compendium/spells/detect-magic-xphb.md), [Fog Cloud](3-Compendium/spells/fog-cloud-xphb.md),\
    \ [Light](3-Compendium/spells/light-xphb.md)\n\n1/day each: [Control Weather](3-Compendium/spells/control-weather-xphb.md),\
    \ [Gaseous Form](3-Compendium/spells/gaseous-form-xphb.md), [Telekinesis](3-Compendium/spells/telekinesis-xphb.md)"
  "name": "Spellcasting"
- "desc": "The giant casts the [Misty Step](3-Compendium/spells/misty-step-xphb.md)\
    \ spell, using the same spellcasting ability as Spellcasting.\n\nAt will:\
    \ [Misty Step](3-Compendium/spells/misty-step-xphb.md)"
  "name": "Misty Step"
"actions":
- "desc": "The giant makes two attacks, using Thunderous Mace or Thundercloud in any\
    \ combination. It can replace one attack with a use of Spellcasting to cast [Fog\
    \ Cloud](3-Compendium/spells/fog-cloud-xphb.md)."
  "name": "Multiattack"
- "desc": "Melee Attack: +12, reach 10 ft. Hit: 21 (3d8 + 8) Bludgeoning damage\
    \ plus 7 (2d6) Thunder damage."
  "name": "Thunderous Mace"
- "desc": "Ranged Attack: +12, range 240 ft. Hit: 18 (3d6 + 8) Thunder damage,\
    \ and the target has the [Incapacitated](3-Compendium/rules/conditions.md#Incapacitated)\
    \ condition until the end of its next turn."
  "name": "Thundercloud"
"source":
- "XMM"
```
^statblock

## Environment

mountain