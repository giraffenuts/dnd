---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Vampire Umbral Lord"]
---
# [Vampire Umbral Lord](3-Compendium\bestiary\undead/vampire-umbral-lord-xmm.md)
*Source: Monster Manual (2024) p. 318*  

Vampire umbral lords embrace their ties to the darkness, devoting themselves to sinister powers in exchange for access to forbidden magic.

## Vampires

*Blood-Sucking Lords of the Night*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Vampires disguise their accursed, immortal natures, passing as mortals to feed on the blood of the living. While the youngest vampires might be little more than bloodthirsty servants of their creators, the eldest possess incredible cunning and control over supernatural forces of the night.

Undead vampires lie dormant during the day, retreating to resting places hidden from foes and the sun's searing rays. Roll on or choose a result from the Vampire Resting Places table to inspire a vampire's grim sanctuary.

**Vampire Resting Places**

`dice: [](vampire-umbral-lord-xmm.md#^vampire-resting-places)`

| dice: 1d6 | The Vampire's Resting Place Is... |
|-----------|-----------------------------------|
| 1 | Among the roots of a dead tree. |
| 2 | At the bottom of a stagnant pool. |
| 3 | A coffin filled with grave dirt. |
| 4 | A large pot full of blood or vinegar. |
| 5 | A space accessible only by shape-shifting. |
| 6 | Within a statue or suit of armor. |
^vampire-resting-places

### Vampire Lairs

Vampires and vampire umbral lords create sanctuaries apart from the living, whether hidden in cosmopolitan cities or sequestered in ruins where they dwelled in life.

> [!quote] A quote from Astarion, Vampire Spawn  
> 
> Darling, you are simply delicious...


```statblock
"name": "Vampire Umbral Lord (XMM)"
"size": "Small or Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"stats":
- !!int "20"
- !!int "18"
- !!int "18"
- !!int "19"
- !!int "16"
- !!int "21"
"speed": "40 ft., climb 40 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "9"
  "Wisdom": !!int "8"
  "Strength": !!int "10"
"skillsaves":
  "Stealth": !!int "9"
  "Perception": !!int "13"
  "Arcana": !!int "9"
"damage_immunities": "cold, necrotic"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion)"
"senses": "blindsight 120 ft., passive Perception 23"
"languages": "Common plus three other languages"
"cr": "15"
"traits":
- "desc": "The vampire casts [Hunger of Hadar](3-Compendium/spells/hunger-of-hadar-xphb.md)\
    \ (level 5 version), requiring no spell components and using Charisma as the spellcasting\
    \ ability (spell save DC 18).\n"
  "name": "Hunger of Hadar (Recharge 5-6)"
- "desc": "The vampire casts [Command](3-Compendium/spells/command-xphb.md), requiring\
    \ no spell components and using Charisma as the spellcasting ability (spell save\
    \ DC 18). The vampire can't take this action again until the start of its next\
    \ turn.\n"
  "name": "Beguile"
- "desc": "If the vampire fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
- "desc": "If the vampire drops to 0 [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)\
    \ outside its resting place, it teleports into its resting place unless it is\
    \ in running water or sunlight. If it can't teleport, it is destroyed. Once inside\
    \ its resting place, it has the [Paralyzed](3-Compendium/rules/conditions.md#Paralyzed)\
    \ condition for 1 hour, after which it regains 1 [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)."
  "name": "Shadow Escape"
- "desc": "The vampire has these weaknesses:\n\n- Forbiddance. The vampire can't\
    \ enter a residence without an invitation from an occupant.  \n- Running Water.\
    \ The vampire takes 20 Acid damage if it ends its turn in running water.  \n-\
    \ Stake to the Heart. If a weapon that deals Piercing damage is driven into\
    \ the vampire's heart while the vampire has the [Incapacitated](3-Compendium/rules/conditions.md#Incapacitated)\
    \ condition in its resting place, the vampire has the [Paralyzed](3-Compendium/rules/conditions.md#Paralyzed)\
    \ condition until the weapon is removed.  \n- Sunlight. The vampire takes\
    \ 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has\
    \ [Disadvantage](3-Compendium/rules/variant-rules/disadvantage-xphb.md) on attack\
    \ rolls and ability checks.  "
  "name": "Vampire Weakness"
"actions":
- "desc": "The vampire makes two attacks, using Grave Strike or Sickening Ray in any\
    \ combination."
  "name": "Multiattack"
- "desc": "Melee Attack: +10, reach 5 ft. Hit: 9 (1d8 + 5) Slashing damage plus\
    \ 13 (3d8) Necrotic damage."
  "name": "Grave Strike"
- "desc": "Ranged Attack: +10, range 120 ft. Hit: 16 (2d10 + 5) Necrotic damage,\
    \ and the target has the [Poisoned](3-Compendium/rules/conditions.md#Poisoned)\
    \ condition until the start of the vampire's next turn."
  "name": "Sickening Ray"
"bonus_actions":
- "desc": "Constitution Saving Throw: DC 18, one creature the vampire can see within\
    \ 30 feet that isn't a Construct or an Undead. Failure: 14 (4d6) Necrotic damage.\
    \ The target's [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)\
    \ maximum decreases by an amount equal to the damage taken, and the vampire regains\
    \ [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md) equal to that\
    \ amount."
  "name": "Sanguine Drain"
"legendary_actions":
- "desc": "The vampire moves up to half its [Speed](3-Compendium/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Grave Strike or Sickening Ray attack."
  "name": "Umbral Strike"
"regional_effects":
- "desc": "The region containing a vampire's lair is warped by its presence, creating\
    \ the following effects:"
  "name": ""
- "desc": "- Children of the Night. The vampire exerts influence over the animals\
    \ in its domain. From dusk until dawn, Medium or smaller Beasts have the [Charmed](3-Compendium/rules/conditions.md#Charmed)\
    \ condition while within 1 mile of the lair.  \n- Looming Shadows. Shadows\
    \ within 1 mile of the lair seem to move as if alive. Any creature (excluding\
    \ the vampire and its allies) that finishes a [Short Rest](3-Compendium/rules/variant-rules/short-rest-xphb.md)\
    \ while within 1 mile of the lair must succeed on a DC 15 Wisdom saving throw\
    \ or gain no benefit from that rest.  \n- Mists. The area within 1 mile of\
    \ the lair is [Lightly Obscured](3-Compendium/rules/variant-rules/lightly-obscured-xphb.md)\
    \ by a persistent, creeping fog. The vampire and any creatures of its choice are\
    \ unaffected by the fog.  "
  "name": ""
- "desc": "If the vampire dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
```
^statblock

## Environment

underdark, urban