---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/fire
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Azer Sentinel"]
---
# [Azer Sentinel](3-Compendium\bestiary\elemental/azer-sentinel-xmm.md)
*Source: Monster Manual (2024) p. 25*  

Azer sentinels defend their communities' smiths and channel their flames through their weapons.

## Azers

*Fiery Smiths of Living Metal*

- **Habitat.** Mountain, Planar (Elemental Plane of Fire)  
- **Treasure.** Armaments, Individual  

Azers are living bronze folk who work the primal elements of creation to craft weapons and magical wonders among the multiverse's mightiest infernos.

```statblock
"name": "Azer Sentinel (XMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "17"
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "10"
"speed": "30 ft."
"saves":
  "Constitution": !!int "4"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Compendium/rules/conditions.md#Poisoned)"
"senses": "passive Perception 11"
"languages": "Primordial (Ignan)"
"cr": "2"
"traits":
- "desc": "At the end of each of the azer's turns, each creature of the azer's choice\
    \ in a 5-foot [Emanation [Area of Effect]](3-Compendium/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from the azer takes 5 (1d10) Fire damage unless the azer has the\
    \ [Incapacitated](3-Compendium/rules/conditions.md#Incapacitated) condition."
  "name": "Fire Aura"
- "desc": "The azer sheds [Bright Light](3-Compendium/rules/variant-rules/bright-light-xphb.md)\
    \ in a 10-foot radius and [Dim Light](3-Compendium/rules/variant-rules/dim-light-xphb.md)\
    \ for an additional 10 feet."
  "name": "Illumination"
"actions":
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 8 (1d10 + 3) Bludgeoning damage\
    \ plus 3 (1d6) Fire damage."
  "name": "Burning Hammer"
"source":
- "XMM"
```
^statblock

## Environment

mountain, planar, fire