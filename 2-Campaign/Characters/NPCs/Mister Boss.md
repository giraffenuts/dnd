---
Tags:
  - Category/Character/NPC
AssociatedGroup:
  - Clock of the Time Dragon
Gender: Male
Race: 
Age: 
Class: 
Alignment: 
Religion:
  - "[[1-The Land of Oz/Religion/Tik-Tokism.md|Tik-Tokism]]"
Character-Role: 
Character-Residence: None
Character-Origin: Earth
Vitality: 
statblock: Commoner
age: 53
race: Dwarf
view-count: 2
alignment: Chaotic Neutral
vitality: Healthy
character-role: Party Guide
profileImage: z_Assets/img/NPCs/MisterBossProfilePortrait.png
---



# `=this.file.name`

Source: `INPUT[suggester(optionQuery("1-The Land of Oz/Characters")):source-link]`

> [!infobox|wfit embed ]+
> # `=this.file.name`
> `INPUT[imageSuggester(optionQuery("z_Assets/img/NPCs")):profileImage]`
> [[ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Attribute |  Description |
> ---|---|
> Origin | `INPUT[suggester(optionQuery(#Category/Location/Settlement), allowOther):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Location/Settlement), allowOther):Character-Residence]` |
> Group  | `INPUT[inlineListSuggester(optionQuery(#Category/Group), allowOther):AssociatedGroup]`|
> Faith  | `INPUT[inlineListSuggester(optionQuery(#Category/Religion),option(Agnostic),option(Atheist),option(Other)):Religion]`|
> Gender | `INPUT[inlineSelect(option(Male), option(Female), option(Nonbinary)):Gender]` |
> Race | `INPUT[text(class(meta-bind-med-width),placeholder(Race)):race]` |
> Age | `INPUT[number(class(meta-bind-tiny-width),placeholder(Age)):age]` |
> Vitality | `INPUT[inlineSelect(option(Healthy), option(Injured), option(Sick), option(Deceased)):vitality]` |
> ###### Rules Info
> Attribute |  Description |
> ---|---|
> Alignment | `INPUT[suggester(option(Lawful Good), option(Neutral Good), option(Chaotic Good), option(Lawful Neutral), option(True Neutral), option(Chaotic Neutral), option(Lawful Evil), option(Neutral Evil), option(Chaotic Evil)):alignment]` |
> Class | `INPUT[suggester(option(Artificer), option(Barbarian), option(Bard), option(Cleric), option(Druid), option(Fighter), option(Monk), option(Paladin), option(Ranger), option(Rogue), option(Sorcerer), option(Warlock), option(Wizard), allowOther):class]` |
> Character Role | `INPUT[text:character-role]` |
> ## Statblocks
> ```statblock
> forcedColumns: true
> columns: 2
> columnWidth: 50%
>name: Mister Boss
>source: Oz
>size: Medium
>type: humanoid
>subtype: Dwarf
>alignment: chaotic neutral
>ac: 11
>hp: 32
>hit_dice: 5d8 + 9
>speed: 30 ft.
>stats:
>  - 15
>  - 11
>  - 14
>  - 10
>  - 10
>  - 12
>skillsaves:
>  - intimidation: 3
>  - performance: 3
>damage_vulnerabilities: ""
>damage_resistances: ""
>damage_immunities: ""
>condition_immunities: ""
>senses: passive Perception 10
>languages: Ozian, English
>cr: 1/2
>bestiary: true
>traits:
>  - name: Leader
>    desc: Mister Boss gives his allies advantage on attack rolls if he is within 5 ft. of them and their target.
>    attack_bonus: 0
>actions:
>  - name: Multiattack
>    desc: Mister Boss makes two melee attacks.
>    attack_bonus: 0
>  - name: Battle hammer
>    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 5 (1d6 + 2) bludgeoning damage."
>    attack_bonus: 4
>    damage_dice: 1d6
>    damage_bonus: 2
>  - name: Heavy Crossbow
>    desc: "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit: 5 (1d10) piercing damage."
>    attack_bonus: 2
>    damage_dice: 1d10
>```
>```encounter
>name: Mister Boss
>creatures:
> - 1: Mister Boss, ally
>```
><br><br>

<br>

>[!quote|c-p-med] Mister Boss
>All our lives are activity without meaning; we burrow rat-like into life and we squirm rat-like through it and rat-like we are flung into our graves at the end. Now and then, why shouldn’t we hear a voice of prophecy, or see a miracle play? Beneath the apparent sham and indignity of our rat-like lives, a humble pattern and meaning still applies! Come nearer, my good people, and watch what a little extra knowledge augurs for your lives! The Time Dragon sees before and beyond and within the truth of your sorry span of years here! Look at what it shows you!


## Profile

**Mister Boss** is a dwarf who claims to be an immortal being sent to Oz to prevent the Grimmerie from returning to Earth. He owns and operates the Clock of the Time Dragon.
