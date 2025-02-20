---
tags:
  - Category/Journal/SessionNotes
session-date: February-23-2025
session-number: 4
items:
  - "[[2-Campaign/Items/Locksmith's Wand.md|Locksmith's Wand]]"
locations:
  - "[[2-Campaign/Locations/Emerald Palace.md|Emerald Palace]]"
  - "[[2-Campaign/Locations/Southstairs.md|Southstairs]]"
npcs:
  - "[[2-Campaign/Characters/NPCs/Mister Boss.md|Mister Boss]]"
  - "[[2-Campaign/Characters/NPCs/Nor Tigelaar.md|Nor Tigelaar]]"
---
**Date**: `INPUT[datePicker:session-date]` **\|** **Session Number**: `INPUT[number(class(meta-bind-tiny-width),placeholder(#)):session-number]`
# Session Prep
## Characters  
  
**Maylo Isle** - *she/her* (Maddie). Human barbarian, age 19. Attacker, damage; high HP, mid AC. 

**Merle Persimmon** - *he/him* (Macy). Human sorcerer, age 25. Spellcaster, damage; low HP, low AC. 

**Scraps** - *she/her* (Julia). Construct artificer, age ~6. Spellcaster, utility, defense; mid HP, high AC. 

**Siegfried "Fried" Salt** - *they/he/she* (Asha). Human bard, age ~35. Spellcaster, utility, healer; low HP, mid AC. 
## Strong Start  
  
Description of your strong start.  
## Scenes  
  
- [ ] **Scene**. Description

## Fantastic Locations  

`INPUT[inlineListSuggester(optionQuery(#Category/Location)):locations]`



<br>

`BUTTON[insert-location-desc,remove-location-desc]`

<br>

## Important NPCs  
  
`INPUT[inlineListSuggester(optionQuery(#Category/Character)):npcs]`


### [[Nor Tigelaar]] 

###### Profile

###### Description

###### Role this session

###### Additional notes
<!-- last-npc-id -->
```meta-bind-button
label: Insert NPC description
icon: plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: "<!-- last-npc-id -->\n"
    replacement: "\n"
    regexpFlags: g
  - type: replaceSelf
    replacement: "z_Templates/5_Meta Bind/Template Button - Insert NPC Description.md"
    templater: true
```

```meta-bind-button
label: Remove last NPC description
icon: minus
style: destructive
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: "((?<!# Additional notes).*)(\n#{3} .*)(?=<!-- last-npc-id -->\n)"
    replacement: "$1"
    regexpFlags: gs
```

## Secrets and Clues  

### For Individuals

###### For Maylo
- [ ] **DC X**: Secret description.

###### For Merle
- [ ] **DC X**: Secret description.

###### For Scraps
- [ ] **DC X**: Secret description. 

###### For Siegfried
- [ ] **DC X**: Secret description.

### For The Party

###### Topic 
- [ ] **DC X**: Secret description.

###### Topic
- [ ] **DC X**: Secret description.

###### Topic
- [ ] **DC X**: Secret description.

## Potential Encounters  

```encounter-table
name: Emerald Palace, Palace Guards
party: Oz
creatures: [2 Guard,Scout,Acolyte,"Mister Boss, ally"]
---
name: Wizard's Study, Gargoyle
party: Oz
creatures: [2 Gargoyle]
---
name: Southstairs, Watchmen
party: Oz
creatures: [3 Clockwork Watchman]
---
name: Southstairs, Death Dogs
party: Oz
creatures: [2 Death Dog]
```


`BUTTON[insert-encounter,remove-encounter]`


<br>

## Potential Items  
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):items]`
`VIEW[### {items[0]}][text(renderMarkdown)]`
- [ ] Found
> [!columns|2 no-title]
>> [!blank]
>> ###### Importance
>> - 
>> ###### Who?
>> - 
>
>> [!blank]
>>###### Where?
>> - 
>> ###### How?
>> - 

<!--
<item-desc>`VIEW[### {items[1]}][text(renderMarkdown)]`
- [ ] Found
> [!columns|2 no-title]
>> [!blank]
>> ###### Importance
>> - 
>> ###### Who?
>> - 
>
>> [!blank]
>>###### Where?
>> - 
>> ###### How?
>> - 

<item-desc>`VIEW[### {items[2]}][text(renderMarkdown)]`
- [ ] Found
> [!columns|2 no-title]
>> [!blank]
>> ###### Importance
>> - 
>> ###### Who?
>> - 
>
>> [!blank]
>>###### Where?
>> - 
>> ###### How?
>> - 

<item-desc>`VIEW[### {items[3]}][text(renderMarkdown)]`
- [ ] Found
> [!columns|2 no-title]
>> [!blank]
>> ###### Importance
>> - 
>> ###### Who?
>> - 
>
>> [!blank]
>>###### Where?
>> - 
>> ###### How?
>> - 

<item-desc>`VIEW[### {items[4]}][text(renderMarkdown)]`
- [ ] Found
> [!columns|2 no-title]
>> [!blank]
>> ###### Importance
>> - 
>> ###### Who?
>> - 
>
>> [!blank]
>>###### Where?
>> - 
>> ###### How?
>> - 
--->

<br>

`BUTTON[insert-item-desc,remove-item-desc]`

<br>

# Session Notes

# Post Session Notes
