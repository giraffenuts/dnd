---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/wizard
statblock: inline
aliases: ["Lich"]
---
# [Lich](3-Compendium\bestiary\undead/lich-xmm.md)
*Source: Monster Manual (2024) p. 196*  

## Lich

*Deathless Master of Magic*

- **Habitat.** Any  
- **Treasure.** Arcana  

Some nefarious magic-users carry out forbidden necromantic rituals that sever their souls from their bodies to turn themselves into liches, masters of magic and undeath. With their souls preserved in hidden relics, liches puppet their own corpses as they pursue ambitions free from mortal bonds.

Liches possess exceptional cunning and magical prowess, and they use their unnatural immortality to pursue arcane secrets few could grasp in a single life. Uncanny agendas lead them to plumb the secrets of life, the multiverse, godhood, and less fathomable topics. Careless of mortal lives or desires, liches go to any lengths to achieve their goals.

A lich's age and origin influences its form. Older liches appear as little more than brittle skeletons clad in the rotten finery of forgotten empires, while younger liches more closely resemble living creatures and are clad in contemporary garb. Many cloak themselves in illusions of their idealized mortal forms.

Although liches don't fear death, they're not free from the ravages of time. Over ages, some liches lose their connection to time and the physical world, degenerating into demiliches.

### Lich Spirit Jars

The process of becoming a lich is involved, dangerous, and unique to each would-be lich. If the rite succeeds, the lich's soul is bound to a spirit jar, a specially prepared magical repository. This relic anchors the lich's spirit to the world and preserves it should the lich's body be destroyed. A lich can be slain only if its spirit jar is ruined. As such, a lich goes to great lengths to hide and protect its spirit jar.

Spirit jars are typically small, well-made objects that were meaningful to a lich in life. Roll on or choose a result from the Lich Spirit Jar table to inspire where a lich hides its soul.

**Lich Spirit Jars**

`dice: [](lich-xmm.md#^lich-spirit-jars)`

| dice: 1d8 | The Lich's Spirit Jar Is... |
|-----------|-----------------------------|
| 1 | A bottle or puzzle box inscribed with sigils. |
| 2 | A contract folded into a paper figure. |
| 3 | The first magic item the lich created. |
| 4 | A hollow figurine of a deity or monster. |
| 5 | An hourglass with its sands floating in stasis. |
| 6 | A locket or signet ring with a noble crest. |
| 7 | A rune-etched egg. |
| 8 | The skull of the lich's mentor. |
^lich-spirit-jars

### Lich Lairs

Liches create secluded libraries of magical lore and arcane laboratories hidden within extraplanar bastions, fortresses with cursed reputations, or other such deadly sanctuaries.

> [!quote] A quote from Rudolph van Richten  
> 
> Ambition can become an addiction of the mind and spirit. It builds beyond a driving flame into an insidious inferno that burns a mage hollow until only the desire for more magical power remains


```statblock
"name": "Lich (XMM)"
"size": "Medium"
"type": "undead"
"subtype": "wizard"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "315"
"hit_dice": "42d8 + 126"
"stats":
- !!int "11"
- !!int "16"
- !!int "16"
- !!int "21"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "10"
  "Wisdom": !!int "9"
  "Intelligence": !!int "12"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "9"
  "History": !!int "12"
  "Arcana": !!int "19"
"damage_resistances": "cold, lightning"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Compendium/rules/conditions.md#Charmed), [exhaustion](3-Compendium/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Compendium/rules/conditions.md#Frightened), [paralyzed](3-Compendium/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Compendium/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 19"
"languages": "all"
"cr": "21"
"traits":
- "desc": "The lich casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 20):\n\nAt will: [Detect Magic](3-Compendium/spells/detect-magic-xphb.md),\
    \ [Detect Thoughts](3-Compendium/spells/detect-thoughts-xphb.md), [Dispel Magic](3-Compendium/spells/dispel-magic-xphb.md),\
    \ [Fireball](3-Compendium/spells/fireball-xphb.md) (level 5 version), [Invisibility](3-Compendium/spells/invisibility-xphb.md),\
    \ [Lightning Bolt](3-Compendium/spells/lightning-bolt-xphb.md) (level 5 version),\
    \ [Mage Hand](3-Compendium/spells/mage-hand-xphb.md), [Prestidigitation](3-Compendium/spells/prestidigitation-xphb.md)\n\
    \n1/day each: [Chain Lightning](3-Compendium/spells/chain-lightning-xphb.md),\
    \ [Finger of Death](3-Compendium/spells/finger-of-death-xphb.md), [Power Word\
    \ Kill](3-Compendium/spells/power-word-kill-xphb.md), [Scrying](3-Compendium/spells/scrying-xphb.md)\n\
    \n2/day each: [Animate Dead](3-Compendium/spells/animate-dead-xphb.md), [Dimension\
    \ Door](3-Compendium/spells/dimension-door-xphb.md), [Plane Shift](3-Compendium/spells/plane-shift-xphb.md)"
  "name": "Spellcasting"
- "desc": "The lich casts [Counterspell](3-Compendium/spells/counterspell-xphb.md)\
    \ or [Shield](3-Compendium/spells/shield-xphb.md) in response to the spell's trigger,\
    \ using the same spellcasting ability as Spellcasting.\n\nAt will: [Counterspell](3-Compendium/spells/counterspell-xphb.md),\
    \ [Shield](3-Compendium/spells/shield-xphb.md)"
  "name": "Protective Magic"
- "desc": "The lich casts [Fear](3-Compendium/spells/fear-xphb.md), using the same\
    \ spellcasting ability as Spellcasting. The lich can't take this action again\
    \ until the start of its next turn.\n"
  "name": "Frightening Gaze"
- "desc": "If the lich fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
- "desc": "If destroyed, the lich reforms in 1d10 days if it has a spirit jar, reviving\
    \ with all its [Hit Points](3-Compendium/rules/variant-rules/hit-points-xphb.md).\
    \ The new body appears in an unoccupied space within the lich's lair."
  "name": "Spirit Jar"
"actions":
- "desc": "The lich makes three attacks, using Eldritch Burst or Paralyzing Touch\
    \ in any combination."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack: +12, reach 5 ft. or range 120 ft. Hit: 31 (4d12\
    \ + 5) Force damage."
  "name": "Eldritch Burst"
- "desc": "Melee Attack: +12, reach 5 ft. Hit: 15 (3d6 + 5) Cold damage, and the\
    \ target has the [Paralyzed](3-Compendium/rules/conditions.md#Paralyzed) condition\
    \ until the start of the lich's next turn."
  "name": "Paralyzing Touch"
"legendary_actions":
- "desc": "The lich teleports up to 60 feet to an unoccupied space it can see, and\
    \ each creature within 10 feet of the space it left takes 11 (2d10) Necrotic damage."
  "name": "Deathly Teleport"
- "desc": "Constitution Saving Throw: DC 20, each creature that isn't an Undead\
    \ in a 20-foot [Emanation [Area of Effect]](3-Compendium/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from the lich. Failure: 31 (9d6) Necrotic damage. Success: Half\
    \ damage. Failure or Success: The lich can't take this action again until the\
    \ start of its next turn."
  "name": "Disrupt Life"
"regional_effects":
- "desc": "The region containing a lich's lair is warped by its presence, creating\
    \ the following effects:"
  "name": ""
- "desc": "- All-Seeing. While in its lair, the lich can cast [Clairvoyance](3-Compendium/spells/clairvoyance-xphb.md),\
    \ requiring no spell components and using the same spellcasting ability as its\
    \ Spellcasting action.  \n- Inevitable Siphon. Whenever a Humanoid dies within\
    \ 1 mile of the lair, its soul is immediately consumed by the lich. A Humanoid\
    \ whose soul is consumed in this way can be brought back to life only by a True\
    \ Resurrection or [Wish](3-Compendium/spells/wish-xphb.md) spell.  "
  "name": ""
- "desc": "If the lich is destroyed or moves its lair elsewhere, these effects end\
    \ immediately. These effects resume if the lich gains a new body (see its Spirit\
    \ Jar trait)."
  "name": ""
"source":
- "XMM"
```
^statblock

## Environment

any