---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Graveyard Revenant"]
---
# [Graveyard Revenant](3-Compendium\bestiary\undead/graveyard-revenant-xmm.md)
*Source: Monster Manual (2024) p. 260*  

Graveyard revenants possess dozens of bodies that combine to form grotesque masses. They take revenge on those responsible for mass deaths or institutions that callously ruin lives.

## Revenants

*Vengeance from beyond the Grave*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** Any  

Wrathful spirits bent on revenge, revenants possess corpses and other materials, using them to seek justice or vent their rage on those who wronged them. Revenants refuse to rest until those they seek to punish are no more. If their bodies are destroyed, revenants claim new forms and continue their ruthless quests.

```statblock
"name": "Graveyard Revenant (XMM)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "161"
"hit_dice": "14d12 + 70"
"stats":
- !!int "20"
- !!int "14"
- !!int "20"
- !!int "13"
- !!int "16"
- !!int "18"
"speed": "40 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Strength": !!int "8"
  "Constitution": !!int "8"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Compendium/rules/conditions.md#Frightened), [paralyzed](3-Compendium/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Compendium/rules/conditions.md#Petrified), [poisoned](3-Compendium/rules/conditions.md#Poisoned),\
  \ [stunned](3-Compendium/rules/conditions.md#Stunned), [unconscious](3-Compendium/rules/conditions.md#Unconscious)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common plus two other languages"
"cr": "7"
"traits":
- "desc": "If the revenant dies, it revives 24 hours later unless [Dispel Evil and\
    \ Good](3-Compendium/spells/dispel-evil-and-good-xphb.md) is cast on its remains.\
    \ If it revives, it animates another group of corpses elsewhere on the same plane\
    \ of existence; it now looks different but uses the same stat block and returns\
    \ with all its [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)."
  "name": "Undead Restoration"
"actions":
- "desc": "The revenant makes two Suffocate attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +8, reach 10 ft. Hit: 10 (1d10 + 5) Bludgeoning damage\
    \ plus 10 (3d6) Necrotic damage. If the target is a Large or smaller creature,\
    \ it has the [Grappled](3-Compendium/rules/conditions.md#Grappled) condition (escape\
    \ DC 15). Until the grapple ends, the target is suffocating. The revenant can\
    \ have up to two targets [Grappled](3-Compendium/rules/conditions.md#Grappled)\
    \ in this way at a time."
  "name": "Suffocate"
- "desc": "Wisdom Saving Throw: DC 15, each creature in a 30-foot [Emanation [Area\
    \ of Effect]](3-Compendium/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from the revenant. Failure: The target has the [Paralyzed](3-Compendium/rules/conditions.md#Paralyzed)\
    \ condition and repeats the save at the end of each of its turns, ending the effect\
    \ on itself on a success. After 1 minute, it succeeds automatically."
  "name": "Haunting Glare (Recharge 5-6)"
"source":
- "XMM"
```
^statblock

## Environment

forest, swamp, urban