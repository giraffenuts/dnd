---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Death Knight"]
---
# [Death Knight](3-Compendium\bestiary\undead/death-knight-xmm.md)
*Source: Monster Manual (2024) p. 92*  

Death knights are deadly combatants and domineering commanders with grim histories. Some strive to end the curses that doom them to undeath, though their selfish souls eternally shackle them to their fates. Others, like the infamous death knight Lord Soth, brood in dismal ruins for centuries, rousing themselves to action only when something reignites their deathless evil.

## Death Knights

*Haunted Commanders of Unliving Legions*

- **Habitat.** Any  
- **Treasure.** Armaments  

Champions of evil, death knights are armor-clad, skeletal warlords. Combining devastating martial prowess and blasphemous magic, these undying tyrants lead unholy legions against the living or brood in cursed citadels. Every death knight is haunted by a legacy of tragedy and dishonor that drives it to commit greater evils.

```statblock
"name": "Death Knight (XMM)"
"size": "Small or Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"hp": !!int "199"
"hit_dice": "21d8 + 105"
"stats":
- !!int "20"
- !!int "11"
- !!int "20"
- !!int "12"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "9"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Compendium/rules/conditions.md#Frightened), [poisoned](3-Compendium/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Abyssal, Common"
"cr": "17"
"traits":
- "desc": "The death knight casts one of the following spells, requiring no Material\
    \ components and using Charisma as the spellcasting ability (spell save DC 18):\n\
    \nAt will: [Command](3-Compendium/spells/command-xphb.md), [Phantom Steed](3-Compendium/spells/phantom-steed-xphb.md)\n\
    \n2/day each: [Destructive Wave](3-Compendium/spells/destructive-wave-xphb.md)\
    \ (Necrotic), [Dispel Magic](3-Compendium/spells/dispel-magic-xphb.md)"
  "name": "Spellcasting"
- "desc": "If the death knight fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The death knight has [Advantage](3-Compendium/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "Undead creatures of the death knight's choice (excluding itself) in a 60-foot\
    \ [Emanation [Area of Effect]](3-Compendium/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from it have [Advantage](3-Compendium/rules/variant-rules/advantage-xphb.md)\
    \ on attack rolls and saving throws. It can't use this trait if it has the [Incapacitated](3-Compendium/rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Marshal Undead"
- "desc": "If the death knight is destroyed before it atones for its evil, it gains\
    \ a new body in 1d10 days, reviving with all its [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md).\
    \ The new body appears in a location significant to the death knight."
  "name": "Undead Restoration"
"actions":
- "desc": "The death knight makes three Dread Blade attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +11, reach 5 ft. Hit: 12 (2d6 + 5) Slashing damage plus\
    \ 13 (3d8) Necrotic damage."
  "name": "Dread Blade"
- "desc": "Dexterity Saving Throw: DC 18, each creature in a 20-foot-radius [Sphere\
    \ [Area of Effect]](3-Compendium/rules/variant-rules/sphere-area-of-effect-xphb.md)\
    \ centered on a point the death knight can see within 120 feet. Failure: 35\
    \ (10d6) Fire damage plus 35 (10d6) Necrotic damage. Success: Half damage."
  "name": "Hellfire Orb (Recharge 5-6)"
"reactions":
- "desc": "Trigger: The death knight is hit by a melee attack roll while holding a\
    \ weapon. Response: The death knight adds 6 to its AC against that attack, possibly\
    \ causing it to miss."
  "name": "Parry"
"legendary_actions":
- "desc": "The death knight uses Spellcasting to cast [Command](3-Compendium/spells/command-xphb.md).\
    \ The death knight can't take this action again until the start of its next turn."
  "name": "Dread Authority"
- "desc": "Constitution Saving Throw: DC 18, one creature the death knight can see\
    \ within 120 feet. Failure: 17 (5d6) Necrotic damage, and the target's [Hit\
    \ Points](3-Compendium/rules/variant-rules/hit-points-xphb.md) maximum decreases\
    \ by an amount equal to the damage taken. Failure or Success: The death knight\
    \ can't take this action again until the start of its next turn."
  "name": "Fell Word"
- "desc": "The death knight moves up to half its [Speed](3-Compendium/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Dread Blade attack."
  "name": "Lunge"
"source":
- "XMM"
```
^statblock

## Environment

any