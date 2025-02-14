---
Tags:
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
view-count: 1
age: 61
race: Human
---



# `=this.file.name`

## Source
`INPUT[suggester(optionQuery("1-The Land of Oz/Characters")):source-link]`

## Profile

**\<Add description here\>**

> [!infobox|right wfit]
> # `=this.file.name`
> ![[ImagePlaceholder.png|cover hsmall]]
> [[ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Origin | `INPUT[suggester(optionQuery(#Category/Location/Settlement), allowOther):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Location/Settlement), allowOther):Character-Residence]` |
> Group  | `INPUT[inlineListSuggester(optionQuery(#Category/Group)):AssociatedGroup]`|
> Faith  | `INPUT[inlineListSuggester(optionQuery(#Category/Religion)):Religion]`|
> Gender | `INPUT[inlineSelect(option(Male), option(Female), option(Nonbinary)):Gender]` |
> Race | `INPUT[text:race]` |
> Age | `INPUT[number:age]` |
> Condition | `INPUT[inlineListSuggester(option(Blinded), option(Charmed), option(Deafened), option(Exhaustion), option(Frightened), option(Grappled), option(Incapacitated), option(Invisible), option(Paralyzed), option(Petrified), option(Poisoned), option(Prone), option(Restrained), option(Stunned), option(Unconscious)):condition]`  |
> Vitality | `INPUT[inlineSelect(option(Healthy), option(Injured), option(Sick), option(Deceased)):vitality]` |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

> [!infobox|left wfit]
> ```statblock
> name: Chyde
> monster: Knight
> columns: 2
> forceColumns: True
> columnWidth: 400px
> ```
<br><br><br><br>

> [!infobox|center wfull]
>```encounter-table
>name: Individual
>creatures:
> - 1: Commoner
>```

