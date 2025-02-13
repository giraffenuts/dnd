---
Tags:
  - Category/Character/NPC
AssociatedGroups: ""
Gender: Male
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Character-Residence: "[[2-Campaign/Locations/Emerald City.md|Emerald City]]"
Character-Origin: 
Vitality: 
view-count: 3
source-link: "[[1-The Land of Oz/Characters/Trism bon Cavalish (Wicked Wiki).md|Trism bon Cavalish (Wicked Wiki)]]"
condition: []
age: 26
race: Human
vitality: Healthy
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
> Origin | `INPUT[suggester(optionQuery(#Category/Location/Settlement)):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Location/Settlement)):Character-Residence]` |
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

## Profile

## Background Story
\<Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?\>

## Statblocks

> [!infobox|center wfit]
> ```statblock
> name: NPC
> monster: Commoner
> columns: 1
> columnWidth: 500px
> ```
<br><br><br><br>

> [!infobox|center wfull]
>```encounter-table
>name: Individual
>creatures:
> - 1: Commoner
>```

