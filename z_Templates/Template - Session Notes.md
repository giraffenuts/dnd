<%*
const hasTitle = !tp.file.title.startsWith("NewSessionNotes");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Session Number");
    await tp.file.move("/2-Campaign/Sessions/" + "Session " + title + "/" + tp.file.title);
    await tp.file.rename("Session " + title + " Notes");
} else {
    title = tp.file.title;
    await tp.file.move("/2-Campaign/Sessions/" + "Session " + title + "/" + tp.file.title);
}
_%>

**Date**: `INPUT[datePicker:session-date]` **\|** **Session Number**: `INPUT[number(class(meta-bind-tiny-width),placeholder(#)):session-number]`
# Session Prep
## Characters  
  
**Maylo Isle** - *she/her* (Maddie). Human barbarian, age 19. Attacker, damage; high HP, mid AC. 

**Merle Persimmon** - *he/him* (Macy). Human sorcerer, age 25. Spellcaster, damage; low HP, low AC. 

**Scraps** - *she/her* (Julia). Construct artificer, age ~6. Spellcaster, utility, defense; mid HP, high AC. 

**Siegfried "Fried" Salt** - *they/them* (Asha). Human bard. Spellcaster, utility, healer; low HP, mid AC. 
## Strong Start  
  
Description of your strong start.  
## Scenes  
  
- [ ] **Scene**. Description

## Fantastic Locations  

`INPUT[inlineListSuggester(optionQuery(#Category/Location)):locations]`

<!--
<location-desc>`VIEW[### {locations[0]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

<location-desc>`VIEW[### {locations[1]}][text(renderMarkdown)]` 

###### Profile

###### Description

###### Role this session 

###### Additional notes

<location-desc>`VIEW[### {locations[2]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session 

###### Additional notes

<location-desc>`VIEW[### {locations[3]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes 

<location-desc>`VIEW[### {locations[4]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

--->

<br>

`BUTTON[insert-location-desc,remove-location-desc]`

<br>

## Important NPCs  
  
`INPUT[inlineListSuggester(optionQuery(#Category/Character)):npcs]`

<!--
<item-desc>`VIEW[### {npcs[0]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

<npc-desc>`VIEW[### {npcs[1]}][text(renderMarkdown)]` 

###### Profile

###### Description

###### Role this session

###### Additional notes

<npc-desc>`VIEW[### {npcs[2]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

<npc-desc>`VIEW[### {npcs[3]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

<npc-desc>`VIEW[### {npcs[4]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session 

###### Additional notes
--->

<br>

`BUTTON[insert-npc-desc,remove-npc-desc]`

<br>

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
name: 
party: Oz
creatures: []
```

`BUTTON[insert-encounter,remove-encounter]`


<br>

## Potential Items  
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):items]`
<!--
<item-desc>`VIEW[### {items[0]}][text(renderMarkdown)]`
- [ ] Found
###### Importance
- 
###### What?
- 
###### Where?
- 
###### How?
- 
###### Who?
- 

<item-desc>`VIEW[### {items[1]}][text(renderMarkdown)]`
- [ ] Found
###### Importance
- 
###### What?
- 
###### Where?
- 
###### How?
- 
###### Who?
- 

<item-desc>`VIEW[### {items[2]}][text(renderMarkdown)]`
- [ ] Found
###### Importance
- 
###### What?
- 
###### Where?
- 
###### How?
- 
###### Who?
- 

<item-desc>`VIEW[### {items[3]}][text(renderMarkdown)]`
- [ ] Found
###### Importance
- 
###### What?
- 
###### Where?
- 
###### How?
- 
###### Who?
- 

<item-desc>`VIEW[### {items[4]}][text(renderMarkdown)]`
- [ ] Found
###### Importance
- 
###### What?
- 
###### Where?
- 
###### How?
- 
###### Who?
- 
--->

<br>

`BUTTON[insert-item-desc,remove-item-desc]`

<br>

# Session Notes

# Post Session Notes
