---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
aliases: ["Rakshasa"]
---
# [Rakshasa](3-Compendium\bestiary\fiend/rakshasa-xmm.md)
*Source: Monster Manual (2024) p. 253*  

## Rakshasa

*Deceiver Hungry for Power and Flesh*

- **Habitat.** Planar (Nine Hells), Urban  
- **Treasure.** Relics  

Masters of manipulation, rakshasas infiltrate communities to claim positions of power. While disguising their true natures, they kidnap victims and indulge their insatiable hunger for flesh.

Rakshasas can withstand some degree of magic, but legends tell of blessed warriors felling them with crossbow bolts, arrows, or similar weapons.

Rakshasas' appearances combine humanlike bodies with the features of animals and monsters. All rakshasas have a physical oddity that remains when they adopt magical disguises, such as palms where the backs of the hands would be on humans.

```statblock
"name": "Rakshasa (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"stats":
- !!int "14"
- !!int "17"
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "20"
"speed": "40 ft."
"skillsaves":
  "Deception": !!int "10"
  "Insight": !!int "8"
  "Perception": !!int "8"
"damage_vulnerabilities": "piercing damage from weapons wielded by creatures under\
  \ the effect of a Bless spell"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [frightened](3-Compendium/rules/conditions.md#Frightened)"
"senses": "truesight 60 ft., passive Perception 18"
"languages": "Common, Infernal"
"cr": "13"
"traits":
- "desc": "The rakshasa casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 18):\n\nAt will:\
    \ [Detect Magic](3-Compendium/spells/detect-magic-xphb.md), [Detect Thoughts](3-Compendium/spells/detect-thoughts-xphb.md),\
    \ [Disguise Self](3-Compendium/spells/disguise-self-xphb.md), [Mage Hand](3-Compendium/spells/mage-hand-xphb.md),\
    \ [Minor Illusion](3-Compendium/spells/minor-illusion-xphb.md)\n\n1/day each:\
    \ [Fly](3-Compendium/spells/fly-xphb.md), [Invisibility](3-Compendium/spells/invisibility-xphb.md),\
    \ [Major Image](3-Compendium/spells/major-image-xphb.md), [Plane Shift](3-Compendium/spells/plane-shift-xphb.md)"
  "name": "Spellcasting"
- "desc": "The rakshasa automatically succeeds on saving throws against spells and\
    \ other magical effects, and the attack rolls of spells automatically miss it.\
    \ Without the rakshasa's permission, no spell can observe the rakshasa remotely\
    \ or detect its thoughts, creature type, or alignment."
  "name": "Greater Magic Resistance"
- "desc": "If the rakshasa dies outside the Nine Hells, its body turns to ichor, and\
    \ it gains a new body instantly, reviving with all its [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md)\
    \ somewhere in the Nine Hells."
  "name": "Fiendish Restoration"
"actions":
- "desc": "The rakshasa makes three Cursed Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +10, reach 5 ft. Hit: 12 (2d6 + 5) Slashing damage plus\
    \ 19 (3d12) Necrotic damage. If the target is a creature, it is cursed. While\
    \ cursed, the target gains no benefit from finishing a [Short Rest](3-Compendium/rules/variant-rules/short-rest-xphb.md)\
    \ or [Long Rest](3-Compendium/rules/variant-rules/long-rest-xphb.md)."
  "name": "Cursed Touch"
- "desc": "Wisdom Saving Throw: DC 18, each enemy in a 30-foot [Emanation [Area\
    \ of Effect]](3-Compendium/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from the rakshasa. Failure: 28 (8d6) Psychic damage, and the target\
    \ has the [Frightened](3-Compendium/rules/conditions.md#Frightened) and [Incapacitated](3-Compendium/rules/conditions.md#Incapacitated)\
    \ conditions until the start of the rakshasa's next turn."
  "name": "Baleful Command (Recharge 5-6)"
"source":
- "XMM"
```
^statblock

## Environment

planar, nine hells, urban