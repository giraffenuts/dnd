---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
aliases: ["Iron Golem"]
---
# [Iron Golem](3-Compendium\bestiary\construct/iron-golem-xmm.md)
*Source: Monster Manual (2024) p. 181*  

## Iron Golem

*Guardian of That Which Must Endure*

- **Habitat.** Any  
- **Treasure.** Any  

Their magical cores protected by mighty armor, iron golems defend important sites and objects. These golems are forged in bipedal forms, the details of which are decided by their creators. Many resemble armored guardians or legendary heroes. Iron golems confront their foes with a combination of overwhelming physical force and eruptions from their magical core. These magical blasts take the form of fiery bolts and poisonous emissions.

Iron golems preserve and protect their charges for generations. Roll on or choose a result from the Iron Golem Orders table to inspire what commands an iron golem follows.

**Iron Golem Orders**

`dice: [](iron-golem-xmm.md#^iron-golem-orders)`

| dice: 1d4 | The Iron Golem Follows Orders To... |
|-----------|-------------------------------------|
| 1 | Block a door that has never been opened, moving only when a prophecy is fulfilled. |
| 2 | Exhale poison gas whenever it can, pausing only when someone speaks a passphrase. |
| 3 | Pose as a statue until a community's hour of greatest need. |
| 4 | Stand atop the resting place of a powerful magic item. |
^iron-golem-orders

```statblock
"name": "Iron Golem (XMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"stats":
- !!int "24"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "fire, poison, psychic"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Compendium/rules/conditions.md#Frightened), [paralyzed](3-Compendium/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Compendium/rules/conditions.md#Petrified), [poisoned](3-Compendium/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands Common plus two other languages but can't speak"
"cr": "16"
"traits":
- "desc": "Whenever the golem is subjected to Fire damage, it regains a number of\
    \ [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md) equal to the\
    \ Fire damage dealt."
  "name": "Fire Absorption"
- "desc": "The golem can't shape-shift."
  "name": "Immutable Form"
- "desc": "The golem has [Advantage](3-Compendium/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack: +12, reach 10 ft. Hit: 20 (3d8 + 7) Slashing damage plus\
    \ 10 (3d6) Fire damage."
  "name": "Bladed Arm"
- "desc": "Ranged Attack: +10, range 120 ft. Hit: 36 (8d8) Fire damage."
  "name": "Fiery Bolt"
- "desc": "Constitution Saving Throw: DC 18, each creature in a 60-foot [Cone [Area\
    \ of Effect]](3-Compendium/rules/variant-rules/cone-area-of-effect-xphb.md). Failure:\
    \ 55 (10d10) Poison damage. Success: Half damage."
  "name": "Poison Breath (Recharge 6)"
"source":
- "XMM"
```
^statblock

## Environment

any