---
tags:
  - Category/Character/NPC
AssociatedGroup: 
Gender: Male
Race: 
Age: 
Class: 
Alignment: 
Religion: 
Character-Role: 
Character-Residence: "[[2-Campaign/Locations/Southstairs.md|Southstairs]]"
Character-Origin: Unknown
Vitality: 
statblock: Commoner
age: 56
race: Human
aliases:
  - Under-mayor
  - Under-mayor of Southstairs
  - Under-mayor Chyde
vitality: Healthy
alignment: Neutral Evil
character-role: Warden and Under-mayor
---



# `=this.file.name`

Source: `INPUT[suggester(optionQuery("1-The Land of Oz/Characters")):source-link]`

> [!infobox|wfit static embed clear-hr]+
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
> name: NPC
> monster: Commoner
> columns: 1
> columnWidth: 400px
> ```
> 
>```encounter-table
>name: Individual
>creatures:
> - 1: Commoner
>```
## Profile

**\<Add description here\>**

