---
session-number: 3
session-date: February-16-2025
locations:
  - "[[2-Campaign/Locations/Emerald City.md|Emerald City]]"
npcs:
  - "[[2-Campaign/Characters/NPCs/Nor Tigelaar.md|Nor Tigelaar]]"
items: []
view-count: 4
---
**Date**: `INPUT[datePicker:session-date]` **\|** **Session Number**: `INPUT[number:session-number]`
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

<br>

>[!recite|no-icon ]- Encounters
>>[!columns| flex 3 no-title]
>>>[!blank]
>>>```encounter
>>>name: Palace Guards
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures: 
>>>  - "2": Guard
>>>  -  "1": Scout
>>>  -  "1": Acolyte
>>>  -  "1": Thug, ally
>>>```
>>>- [ ] Complete
>>>___
>>>```encounter
>>>name: Encounter
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": 
>>>```
>>>- [ ] Complete
>>
>>>[!blank]
>>>```encounter
>>>name: Encounter
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": 
>>>```
>>>- [ ] Complete
>>>___
>>>```encounter
>>>name: Encounter
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": 
>>>```
>>>- [ ] Complete
>>
>>>[!blank]
>>>```encounter
>>>name: Encounter
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": 
>>>```
>>>- [ ] Complete
>>>___
>>>```encounter
>>>name: Encounter
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": 
>>>```
>>>- [ ] Complete
>>

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

