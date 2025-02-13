---
session-number: 3
session-date: February-16-2025
locations: []
npcs: []
items: []
view-count: 2
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
`VIEW[### {locations[0]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

<location-desc>`VIEW[### {locations[1]}][text(renderMarkdown)]` 

###### Profile

###### Description

###### Role this session

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

```meta-bind-button
label: Insert location description
icon: plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: "insert-location-desc"
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: <!--([^`]`.*[^`]*)<location-desc>
    replacement: "$1<!--\n"
    regexpFlags: gm

```

<br>

## Important NPCs  
  
`INPUT[inlineListSuggester(optionQuery(#Category/Character)):npcs]`
<!--
`VIEW[### {npcs[0]}][text(renderMarkdown)]`

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

```meta-bind-button
label: Insert NPC description
icon: plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: "insert-npc-desc"
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: <!--([^`]`.*[^`]*)<npc-desc>
    replacement: "$1<!--\n"
    regexpFlags: gm

```

<br>

## Secrets and Clues  

`INPUT[number(class(small-box))]`

### For Individuals
>[!columns|wfull no-title]
>>[!blank]
>>#### For Maylo
>>- [ ] **DC X**: Secret description.
>><!-- maylo-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: "<!-- maylo-secret -->"
>>    replacement: "- [ ] **DC X**: Secret description.\n>><!-- maylo-secret -->"
>>    regexpFlags: ""
>>```
>>#### For Scraps
>>- [ ] **DC X **: Secret description. 
>><!-- scraps-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: "<!-- scraps-secret -->"
>>    replacement: "- [ ] **DC X**: Secret description.\n>><!-- scraps-secret -->"
>>    regexpFlags: ""
>>```
>
>>[!blank]
>>#### For Merle
>>- [ ] **DC X**: Secret description.
>><!-- merle-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: "<!-- merle-secret -->"
>>    replacement: "- [ ] **DC X**: Secret description.\n>><!-- merle-secret -->"
>>    regexpFlags: ""
>>```
>>#### For Siegfried
>>- [ ] **DC X**: Secret description.
>><!-- siegfried-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: "<!-- siegfried-secret -->"
>>    replacement: "- [ ] **DC X**: Secret description.\n>><!-- siegfried-secret -->"
>>    regexpFlags: ""
>>```

### For The Party
>[!columns|wfull no-title]
>>[!blank]
>>###### Topic: 
>>- [ ] **DC X**: Secret description.
>><!-- party-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: (<!-- party[^`].*[^`]*-->)[^\)>]
>>    replacement: "- [ ] **DC X**: Secret description.\n>>$1\n"
>>    regexpFlags: "gm"
>>```
>>###### Topic: 
>>- [ ] **DC X**: Secret description.
>><!-- party-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: (<!-- party[^`].*[^`]*-->)[^\)>]
>>    replacement: "- [ ] **DC X**: Secret description.\n>>$1\n"
>>    regexpFlags: "gm"
>>```
>
>>[!blank]
>>###### Topic: 
>>- [ ] **DC X**: Secret description.
>><!-- party-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: (<!-- party[^`].*[^`]*-->)[^\)>]
>>    replacement: "- [ ] **DC X**: Secret description.\n>>$1\n"
>>    regexpFlags: "gm"
>>```
>>###### Topic: 
>>- [ ] **DC X**: Secret description.
>><!-- party-secret -->
>>```meta-bind-button
>>label: ""
>>icon: plus
>>style: primary
>>class: ""
>>cssStyle: ""
>>backgroundImage: ""
>>tooltip: "Add a new secret"
>>id: ""
>>hidden: false
>>actions:
>>  - type: regexpReplaceInNote
>>    regexp: (<!-- party[^`].*[^`]*-->)[^\)>]
>>    replacement: "- [ ] **DC X**: Secret description.\n>>$1\n"
>>    regexpFlags: "gm"
>>```

## Potential Encounters  

<br>

>[!recite|no-icon ]- Encounters
>>[!columns| flex 3 no-title]
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

```meta-bind-button
label: Insert item description
icon: plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: "insert-item-desc"
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: <!--([^`]`.*[^`]*)<item-desc>
    replacement: "$1<!--\n"
    regexpFlags: gm

```

<br>

# Session Notes

# Post Session Notes

