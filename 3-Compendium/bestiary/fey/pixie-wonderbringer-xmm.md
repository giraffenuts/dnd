---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Pixie Wonderbringer"]
---
# [Pixie Wonderbringer](3-Compendium\bestiary\fey/pixie-wonderbringer-xmm.md)
*Source: Monster Manual (2024) p. 244*  

Energetic entertainers, wonderbringers use their magic in defense of the wilderness when they must.

## Pixies

*Friends of the Forest*

- **Habitat.** Forest, Planar (Feywild)  
- **Treasure.** Arcana  

Barely a foot tall, pixies resemble diminutive elves with gossamer wings. They invisibly observe those who enter their wooded homes, revealing themselves to those with friendly intentions. Those who are unfriendly become the targets of pixies' pranks.

```statblock
"name": "Pixie Wonderbringer (XMM)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "60"
"hit_dice": "24d4"
"stats":
- !!int "2"
- !!int "20"
- !!int "10"
- !!int "11"
- !!int "14"
- !!int "18"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "5"
  "Arcana": !!int "3"
"senses": "passive Perception 15"
"languages": "Common, Elvish, Sylvan"
"cr": "5"
"traits":
- "desc": "The pixie casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Dancing Lights](3-Compendium/spells/dancing-lights-xphb.md), [Druidcraft](3-Compendium/spells/druidcraft-xphb.md),\
    \ [Invisibility](3-Compendium/spells/invisibility-xphb.md) (self only)\n\n1/day\
    \ each: [Detect Thoughts](3-Compendium/spells/detect-thoughts-xphb.md), [Fly](3-Compendium/spells/fly-xphb.md),\
    \ [Major Image](3-Compendium/spells/major-image-xphb.md)"
  "name": "Spellcasting"
- "desc": "The pixie casts [Entangle](3-Compendium/spells/entangle-xphb.md), [Polymorph](3-Compendium/spells/polymorph-xphb.md),\
    \ or [Tasha's Hideous Laughter](3-Compendium/spells/tashas-hideous-laughter-xphb.md),\
    \ requiring no Material components and using the same spellcasting ability as\
    \ Spellcasting.\n"
  "name": "Burst of Wonder (Recharge 5-6)"
- "desc": "The pixie has [Advantage](3-Compendium/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The pixie makes two Faerie Dust attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack: +7, reach 5 ft. or range 60 ft. Hit: 15 (2d10\
    \ + 4) Radiant damage, and the target has the [Charmed](3-Compendium/rules/conditions.md#Charmed)\
    \ or [Poisoned](3-Compendium/rules/conditions.md#Poisoned) condition (pixie's\
    \ choice) until the start of the pixie's next turn."
  "name": "Faerie Dust"
"source":
- "XMM"
```
^statblock

## Environment

forest, planar, feywild