---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Swarm of Ravens"]
---
# [Swarm of Ravens](3-Compendium\bestiary\beast/swarm-of-ravens-xmm.md)
*Source: Monster Manual (2024) p. 371*  

```statblock
"name": "Swarm of Ravens (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "6"
- !!int "14"
- !!int "12"
- !!int "5"
- !!int "12"
- !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [frightened](3-Compendium/rules/conditions.md#Frightened),\
  \ [grappled](3-Compendium/rules/conditions.md#Grappled), [paralyzed](3-Compendium/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Compendium/rules/conditions.md#Petrified), [prone](3-Compendium/rules/conditions.md#Prone),\
  \ [restrained](3-Compendium/rules/conditions.md#Restrained), [stunned](3-Compendium/rules/conditions.md#Stunned)"
"senses": "passive Perception 15"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny raven. The swarm can't\
    \ regain [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md) or\
    \ gain [Temporary Hit Points](3-Compendium/rules/variant-rules/temporary-hit-points-xphb.md)."
  "name": "Swarm"
"actions":
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 5 (1d6 + 2) Piercing damage, or\
    \ 2 (1d4) Piercing damage if the swarm is [Bloodied](3-Compendium/rules/variant-rules/bloodied-xphb.md)."
  "name": "Beaks"
- "desc": "Wisdom Saving Throw: DC 10, one creature in the swarm's space. Failure:\
    \ The target has the [Deafened](3-Compendium/rules/conditions.md#Deafened) condition\
    \ until the start of the swarm's next turn. While [Deafened](3-Compendium/rules/conditions.md#Deafened),\
    \ the target also has [Disadvantage](3-Compendium/rules/variant-rules/disadvantage-xphb.md)\
    \ on ability checks and attack rolls."
  "name": "Cacophony (Recharge 6)"
"source":
- "XMM"
```
^statblock

## Environment

hill, swamp, urban