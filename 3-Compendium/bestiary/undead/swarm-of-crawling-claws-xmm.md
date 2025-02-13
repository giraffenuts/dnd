---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Swarm of Crawling Claws"]
---
# [Swarm of Crawling Claws](3-Compendium\bestiary\undead/swarm-of-crawling-claws-xmm.md)
*Source: Monster Manual (2024) p. 83*  

Swarms of crawling claws are typically animated by depraved necromancers. Occasionally, these grotesque swarms arise from mass graves or after tragedies, refusing to let their murderers escape their grasp.

## Crawling Claws

*Severed Appendages with Malicious Will*

- **Habitat.** Any  
- **Treasure.** None  

Crawling claws are severed hands that move and act of their own murderous accord. These deathless appendages can spring to life from the severed limbs of killers and villains, and sinister magic-users might animate crawling claws as foul servants. Crawling claws appear in a variety of forms, from decaying human hands to the fresh appendages of animals or monsters

> [!quote] A quote from Ansolm Haas  
> 
> Is it possible for any creature, any living being, to be inherently evil? Such an assertion may itself facilitate the committing of evil acts. By defining a person as evil, we give them free rein to behave as they will, absolving them from the wickedness of their words and the evil of their hands.


```statblock
"name": "Swarm of Crawling Claws (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "49"
"hit_dice": "11d8"
"stats":
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "5"
- !!int "10"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Compendium/rules/conditions.md#Frightened), [grappled](3-Compendium/rules/conditions.md#Grappled),\
  \ [incapacitated](3-Compendium/rules/conditions.md#Incapacitated), [paralyzed](3-Compendium/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Compendium/rules/conditions.md#Petrified), [poisoned](3-Compendium/rules/conditions.md#Poisoned),\
  \ [prone](3-Compendium/rules/conditions.md#Prone), [restrained](3-Compendium/rules/conditions.md#Restrained),\
  \ [stunned](3-Compendium/rules/conditions.md#Stunned)"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "understands Common but can't speak"
"cr": "3"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny creature. The swarm can't\
    \ regain [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md) or\
    \ gain [Temporary Hit Points](3-Compendium/rules/variant-rules/temporary-hit-points-xphb.md)."
  "name": "Swarm"
"actions":
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 20 (4d8 + 2) Necrotic damage, or\
    \ 11 (2d8 + 2) Necrotic damage if the swarm is [Bloodied](3-Compendium/rules/variant-rules/bloodied-xphb.md).\
    \ If the target is a Medium or smaller creature, it has the [Prone](3-Compendium/rules/conditions.md#Prone)\
    \ condition."
  "name": "Swarm of Grasping Hands"
"source":
- "XMM"
```
^statblock

## Environment

any