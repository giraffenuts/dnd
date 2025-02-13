---
Tags:
  - Category/Character/PC
AssociatedGroup: ""
Gender:
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Character-Residence: 
Character-Origin: 
Vitality:
---

<% await tp.file.move("/2-Campaign/Characters/PCs/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter PC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


# `=this.file.name`
## Profile

**\<Add description here\>**

> [!infobox|center wfull]+
> # `=this.file.name`
> ![[ImagePlaceholder.png|cover hsmall]]
> [[ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Origin | `INPUT[suggester(optionQuery(#Category/Place)):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Place)):Character-Residence]` |
> Group  |`INPUT[inlineList:AssociatedGroup]` | 
> Gender | `INPUT[inlineSelect(option(Male), option(Female), option(Nonbinary)):Gender]` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

> [!infobox|center wfull]+
> ```statblock
> name: Individual
> monster: Commoner
> columns: 1
> columnWidth: 650px
> ```

```encounter-table
name: Individual
creatures:
 - 1: Commoner
```

