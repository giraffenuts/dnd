---
Tags:
  - Category/Character/NPC
AssociatedGroup: 
Gender: 
Race: 
Age: 
Class: 
Alignment: 
Religion:
Character-Role: 
Character-Residence: 
Character-Origin: 
Vitality: 
statblock: Commoner
---

<% await tp.file.move("/2-Campaign/Characters/NPCs/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


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

> [!infobox|left wfit]
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

