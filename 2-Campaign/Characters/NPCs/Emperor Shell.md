---
Tags:
  - Category/Character/NPC
AssociatedGroup: 
Gender: Male
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Character-Residence: "[[2-Campaign/Locations/Emerald City.md|Emerald City]]"
Character-Origin: 
Vitality: 
statblock: Commoner
source-link: "[[1-The Land of Oz/Characters/Shell Thropp (Wicked Wiki).md|Shell Thropp (Wicked Wiki)]]"
race: Human
age: 55
vitality: Healthy
Religion:
  - "[[1-The Land of Oz/Religion/Unionism.md|Unionism]]"
---



# `=this.file.name`

## Source
`INPUT[suggester(optionQuery("1-The Land of Oz/Characters")):source-link]`

## Profile

> [!infobox|right wfit]
> # `=this.file.name`
> `INPUT[imageSuggester(optionQuery("z_Assets/img/NPCs")):profileImage]`
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Origin | `INPUT[suggester(optionQuery(#Category/Location/Settlement)):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Location/Settlement)):Character-Residence]` |
> Group  | `INPUT[inlineListSuggester(optionQuery(#Category/Group), allowOther):AssociatedGroup]`|
> Faith  | `INPUT[inlineListSuggester(optionQuery(#Category/Religion)):Religion]`|
> Gender | `INPUT[inlineSelect(option(Male), option(Female), option(Nonbinary)):Gender]` |
> Race | `INPUT[text(class(meta-bind-med-width),placeholder(Race)):race]` |
> Age | `INPUT[number(class(meta-bind-tiny-width),placeholder(Age)):age]` |
> Condition | `INPUT[inlineListSuggester(option(Blinded), option(Charmed), option(Deafened), option(Exhaustion), option(Frightened), option(Grappled), option(Incapacitated), option(Invisible), option(Paralyzed), option(Petrified), option(Poisoned), option(Prone), option(Restrained), option(Stunned), option(Unconscious)):condition]`  |
> Vitality | `INPUT[inlineSelect(option(Healthy), option(Injured), option(Sick), option(Deceased)):vitality]` |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

**\<Short Description\>**

## Background Story

Sheltergod "Shell" Heart is the illegitimate child of Melena Thropp and Turtle Heart. Ashamed by Elphaba's birth, Frexspar abandons his family for a year to live a hermitic lifestyle, spreading the word of the Unnamed god. Still shaken from the unusual circumstances of Elphaba's birth and her husband's abandonment, Melena finds comfort in an affair with a Munchkinlander named Turtle Heart. Upon his return, Frexspar discovers that his wife is pregnant with another man's child. While he was initially furious and threatened to leave Melena and Elphaba for good, Frexspar's faith led him to stay with his wife and raise the illegitimate child. Although, one should not confuse this pious act with forgiveness, for Frexspar never did forgive his wife for her betrayal — of neither her infidelity nor Elphaba's birth. 

At the time of Shell's birth, Frexspar wanted nothing to do with him. In fact, Frexspar wasn't even in town. As a reminder for her love for Turtle Heart, Melena named him Sheltergod or "Shell" for short. When Frexspar discovered Melena had delivered a boy with a normal skin tone, he was slightly relieved, despite being bitter that the child was not his own. However, his indignation continued to grow until it overwhelmed his feeling of responsibility to his family. Frexspar was scarcely involved in the boy's early life and Melena was often too overwhelmed by anguish to even bring herself to look at him, since he was a constant reminder of his true father, Turtle Heart. The absence of his parents was filled by the Thropp's nanny, Cattery Spunge, who was already used to raising Elphaba on her own.

A couple years later, Melena died during Nessarose's birth, leaving Frexspar without a true son. After a period of grief and anger, Frex began to warm up to Shell, realizing he might be the only son he'll ever get. Through a gradual change of heart, Frexspar decided to legally adopt Shell, becoming significantly more involved in his childhood. As he got older, Shell gained more of his father's trust, who was pleased by his involvement in the Union Church and his growing protectiveness of his younger sister, Nessarose. 

Despite being fairly close as young children under Nanny's care, in their teenage years, Shell and Elphaba never got along. Shell adopted his father's resentment for Elphaba, while Elphaba grew spiteful of her father's clear favoritism for a child that was not even his. Feeling caught in the middle of her siblings, 

## Statblocks
> [!infobox|left wfull]
> ```statblock
> name: Emperor Shell
> monster: Archmage 
> forceColumns: true
> columns: 2
> columnWidth: 400px
> ```

<br><br><br><br>

> [!infobox|wfull]
>```encounter-table
>name: Emperor Shell
>creatures:
> - 1: Emperor Shell
>```