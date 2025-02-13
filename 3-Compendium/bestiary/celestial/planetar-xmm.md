---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial/angel
statblock: inline
aliases: ["Planetar"]
---
# [Planetar](3-Compendium\bestiary\celestial/planetar-xmm.md)
*Source: Monster Manual (2024) p. 245*  

## Planetar

*Righteously Wrathful Angelic Warrior*

- **Habitat.** Planar (Upper Planes)  
- **Treasure.** Relics  

Planetars deliver the punishment of righteous gods. These angels innately know truth from lies, and they use magic and blessed weapons to protect the just and root out wickedness across the Multiverse.

These angels act where they can against overwhelming evil, but to avoid the attention of the Lower Planes, they prefer to let mortals attend to affairs on the Material Plane. Planetars often choose mortal champions to oppose threats they're loath to face directly, involving themselves only if necessary. Roll on or choose a result from the Planetar Quests table to inspire what evil a planetar might recruit heroes to thwart.

**Planetar Quests**

`dice: [](planetar-xmm.md#^planetar-quests)`

| dice: 1d6 | The Planetar Entreats a Mortal Hero To... |
|-----------|-------------------------------------------|
| 1 | Convince a villain to meet with the angel. |
| 2 | Find a loved one a villain believes is dead. |
| 3 | Heal the loved one of an evil ruler. |
| 4 | Inspire the defenders of a besieged holy site. |
| 5 | Recover and destroy an evil Artifact. |
| 6 | Reveal the true name of a devil to banish it. |
^planetar-quests

```statblock
"name": "Planetar (XMM)"
"size": "Large"
"type": "celestial"
"subtype": "angel"
"alignment": "Lawful Good"
"ac": !!int "19"
"hp": !!int "262"
"hit_dice": "21d10 + 147"
"stats":
- !!int "24"
- !!int "20"
- !!int "24"
- !!int "19"
- !!int "22"
- !!int "25"
"speed": "40 ft., fly 120 ft. (hover)"
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "11"
  "Strength": !!int "12"
  "Constitution": !!int "12"
"skillsaves":
  "Perception": !!int "11"
"damage_resistances": "radiant"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Compendium/rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all; telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "The planetar casts one of the following spells, requiring no Material components\
    \ and using Charisma as spellcasting ability (spell save DC 20):\n\nAt will:\
    \ [Detect Evil and Good](3-Compendium/spells/detect-evil-and-good-xphb.md)\n\n\
    1/day each: [Commune](3-Compendium/spells/commune-xphb.md), [Control Weather](3-Compendium/spells/control-weather-xphb.md),\
    \ [Dispel Evil and Good](3-Compendium/spells/dispel-evil-and-good-xphb.md), [Raise\
    \ Dead](3-Compendium/spells/raise-dead-xphb.md)"
  "name": "Spellcasting"
- "desc": "The planetar casts [Cure Wounds](3-Compendium/spells/cure-wounds-xphb.md),\
    \ [Invisibility](3-Compendium/spells/invisibility-xphb.md), [Lesser Restoration](3-Compendium/spells/lesser-restoration-xphb.md),\
    \ or [Remove Curse](3-Compendium/spells/remove-curse-xphb.md), using the same\
    \ spellcasting ability as Spellcasting.\n\n2/day: [Cure Wounds](3-Compendium/spells/cure-wounds-xphb.md),\
    \ [Invisibility](3-Compendium/spells/invisibility-xphb.md), [Lesser Restoration](3-Compendium/spells/lesser-restoration-xphb.md),\
    \ [Remove Curse](3-Compendium/spells/remove-curse-xphb.md)"
  "name": "Divine Aid (2/Day)"
- "desc": "The planetar knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "If the planetar dies outside Mount Celestia, its body disappears, and it\
    \ gains a new body instantly, reviving with all its [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)\
    \ somewhere in Mount Celestia."
  "name": "Exalted Restoration"
- "desc": "The planetar has [Advantage](3-Compendium/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The planetar makes three Radiant Sword attacks or uses Holy Burst twice."
  "name": "Multiattack"
- "desc": "Melee Attack: +12, reach 10 ft. Hit: 14 (2d6 + 7) Slashing damage plus\
    \ 18 (4d8) Radiant damage."
  "name": "Radiant Sword"
- "desc": "Dexterity Saving Throw: DC 20, each enemy in a 20-foot-radius [Sphere\
    \ [Area of Effect]](3-Compendium/rules/variant-rules/sphere-area-of-effect-xphb.md)\
    \ centered on a point the planetar can see within 120 feet. Failure: 24 (7d6)\
    \ Radiant damage. Success: Half damage."
  "name": "Holy Burst"
"source":
- "XMM"
```
^statblock

## Environment

planar, upper