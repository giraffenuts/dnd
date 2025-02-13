---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Wraith"]
---
# [Wraith](3-Compendium\bestiary\undead/wraith-xmm.md)
*Source: Monster Manual (2024) p. 336*  

## Wraith

*Essence of Evil*

- **Habitat.** Planar (Shadowfell), Underdark  
- **Treasure.** None  

Wraiths are spectral evils, life-hungry embodiments of malice and terror. Arising from the souls of tyrants, moments of catastrophic pain, or magical blasphemies, wraiths spread suffering and the torment of undeath. Humanoids that die near a wraith might be entrapped by the foul spirit and rise as specters bound to the wraith's sinister will.

Wraiths lurk in forgotten dungeons, accursed ruins, or lands influenced by sinister planes of existence. Such haunted domains might bear hints of the tragedies or foul magic that brought the wraiths into being.

Wraiths might arise from a single powerfully evil soul or other baleful forces. Roll on or choose a result from the Wraith Manifestations table to inspire the wickedness a wraith embodies.

**Wraith Manifestations**

`dice: [](wraith-xmm.md#^wraith-manifestations)`

| dice: 1d10 | The Wraith Embodies... |
|------------|------------------------|
| 1 | The blasphemous magic of a cursed location. |
| 2 | The exorcised evil of a redeemed villain. |
| 3 | A legendary villain who returns once a century. |
| 4 | Locals' fear of a superstition or legend. |
| 5 | The memory of a tragedy. |
| 6 | A profane idea or foul piece of lore. |
| 7 | The torment of one or more suffering souls. |
| 8 | The viciousness of a profane Artifact. |
| 9 | The vile dreams of a slumbering god. |
| 10 | The voracity of a life-hungry realm, such as the Shadowfell or Negative Plane. |
^wraith-manifestations

```statblock
"name": "Wraith (XMM)"
"size": "Small or Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "6"
- !!int "16"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "15"
"speed": "5 ft., fly 60 ft. (hover)"
"damage_resistances": "acid, bludgeoning, cold, fire, piercing, slashing"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Compendium/rules/conditions.md#Grappled), [paralyzed](3-Compendium/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Compendium/rules/conditions.md#Petrified), [poisoned](3-Compendium/rules/conditions.md#Poisoned),\
  \ [prone](3-Compendium/rules/conditions.md#Prone), [restrained](3-Compendium/rules/conditions.md#Restrained),\
  \ [unconscious](3-Compendium/rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common plus two other languages"
"cr": "5"
"traits":
- "desc": "The wraith can move through other creatures and objects as if they were\
    \ [Difficult Terrain](3-Compendium/rules/variant-rules/difficult-terrain-xphb.md).\
    \ It takes 5 (1d10) Force damage if it ends its turn inside an object."
  "name": "Incorporeal Movement"
- "desc": "While in sunlight, the wraith has [Disadvantage](3-Compendium/rules/variant-rules/disadvantage-xphb.md)\
    \ on ability checks and attack rolls."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Attack: +6, reach 5 ft. Hit: 21 (4d8 + 3) Necrotic damage. If\
    \ the target is a creature, its [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)\
    \ maximum decreases by an amount equal to the damage taken."
  "name": "Life Drain"
- "desc": "The wraith targets a Humanoid corpse within 10 feet of itself that has\
    \ been dead for no longer than 1 minute. The target's spirit rises as a [Specter](3-Compendium/bestiary/undead/specter-xmm.md)\
    \ in the space of its corpse or in the nearest unoccupied space. The specter is\
    \ under the wraith's control. The wraith can have no more than seven specters\
    \ under its control at a time."
  "name": "Create Specter"
"source":
- "XMM"
```
^statblock

## Environment

planar, shadowfell, underdark