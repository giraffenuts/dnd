---
tags:
  - Category/SessionNote
session-number: 3
session-date: February-16-2025
locations:
  - "[[2-Campaign/Locations/Emerald City.md|Emerald City]]"
  - "[[2-Campaign/Locations/Southstairs.md|Southstairs]]"
npcs:
  - "[[2-Campaign/Characters/NPCs/Mister Boss.md|Mister Boss]]"
  - "[[2-Campaign/Characters/NPCs/Nor Tigelaar.md|Nor Tigelaar]]"
  - "[[2-Campaign/Characters/NPCs/Chyde.md|Chyde]]"
items: 
view-count: 3
---
**Date**: `INPUT[datePicker:session-date]` **\|** **Session Number**: `INPUT[number(class(meta-bind-tiny-width)):session-number]`
# Session Prep
## Characters  
  
**Maylo Isle** - *she/her* (Maddie). Human barbarian, age 19. Attacker, damage; high HP, mid AC. 

**Merle Persimmon** - *he/him* (Macy). Human sorcerer, age 25. Spellcaster, damage; low HP, low AC. 

**Scraps** - *she/her* (Julia). Construct artificer, age ~6. Spellcaster, utility, defense; mid HP, high AC. 

**Siegfried "Fried" Salt** - *they/them* (Asha). Human bard. Spellcaster, utility, healer; low HP, mid AC. 
## Strong Start  
  
Description of your strong start.  
## Scenes  

###### The Clock of the Time Dragon

>[!aside|center wfull]-
> ###### Description
> - The clock was being drawn by four horses and escorted by a cohort of avant garde performers led by an eccentric dwarf. The dwarf has long jet black hair and a thick beard, with braids bound by golden rings. The dwarf wore a long, flowing cloak, woven from a fine forest green fabric and adorned with golden embroidery. Beneath the cloak, a dark brown leather vest with vinelike engravings sits snugly over a deep green tunic. He wore brown leather boots over beige pleated slacks. A golden pocket watch, a small burlap pouch, and a dagger, all hang from the leather belt around waist. His hands are decorated with golden rings and colorful gemstones.
> 
> - The clock's broad roof was crowned by a wood-carved dragon. It looked poised as if ready to spring, like it was invested with life. There was a house on the stage, decorated in carnival colors, burnished with gold leaf.
> ###### Events
> - The dwarf calls out to the crowd *“All our lives are activity without meaning; we burrow rat-like into life and we squirm rat-like through it and rat-like we are flung into our graves at the end. Now and then, why shouldn’t we hear a voice of prophecy, or see a miracle play? Beneath the apparent sham and indignity of our rat-like lives, a humble pattern and meaning still applies! Come nearer, my good people, and watch what a little extra knowledge augurs for your lives! The Time Dragon sees before and beyond and within the truth of your sorry span of years here! Look at what it shows you!”*

###### Entering the Palace
>[!aside|center wfull]-
> -

###### Entering Southstairs
>[!aside|center wfull]-
> -


## Fantastic Locations  

`INPUT[inlineListSuggester(optionQuery(#Category/Location)):locations]`

`VIEW[### {locations[0]}][text(renderMarkdown)]`

###### Profile
The Emerald City is the social, political, military, and economic imperial capital of the Land of Oz. The city is also located in the exact center of the land and is the nation's largest and most significant settlement.
###### Description
>[!quote] Liir’s description of the city
>The view was like a model of a city made with an impossibly deft hand -hundreds and hundreds of buildings, grand and humble, glazed with tile and black with soot. A city built on a gentle rise, he could now see: long slicing boulevards and curving promenades, a honeycomb of streets and canals, parks and squares, a thousand mews, ten thousand alleys, a hundred thousand windows blinking bronzely. A glowing organ, like the illuminated heart of Oz itself pushed through the flesh of the land, pulsing with its own life, tricked out with monuments, defaced with the graffiti of broken trees, the Palace of the Wizard a cancer upon the landscape, the dead center of it all.
###### Role this session
- The Clock of the Time Dragon is here and the party needs help from Mister Boss
- Need to find an entrance to Southstairs
###### Additional notes

`VIEW[### {locations[1]}][text(renderMarkdown)]` 

###### Profile
Most of what folks know about the Southstairs can be summed up to rumors of the massive prison beneath the Emerald streets. But, there's more to the under-city than what it's known for. Southstairs is more than a prison, it is a fully functioning, albeit horrific, city. It inhabits a broad range of civilians, merchants, artisans, and public officials. Many Animals who do not have the means to get visas to the Free State of Munchkinland choose to move into the under-city's Free District before they are rounded up and sent to the Cages by the Home Guard. Despite its role of holding the Emerald City's most 'dangerous' individuals, the Southstairs prison complex is within the Under-mayor's jurisdiction, allowing the Home Guard to focus on patrolling the surface.

The first layer of the under-city is often referred to as the =='Free District'== or '==Upper District==' and is comprised of the Under-Mayor's Ward, Market Square, and the Hive Ward, among other facilities that help Southstairs run as a 'regular' city.  The second layer, however, is reserved for the prisoners and those who maintain it. Unsurprisingly, it is called the '==Prison Layer==' or the '==Prison District==' and is connected to the Upper District through the Watchman's Ward. This is where most of the guards and prison operators reside. The other wards on the Prison Layer are the Cages, Outer, Inner, and Central wards. Although there are many other areas within the sprawling network of mines and passages that make up Southstairs, these two districts are all that the Under-Mayor cares to maintain.
###### Description
- Cold and damp
- Dark and echoey
- Dirt paths, crushed cement, rotting wooden rails, scattered debris, and mossy stone walls
- Small canals and waterways reminiscent of sewers

>[!quote] Son of a Witch
>The way was dank and sour, sometimes cut with a sulfurous gust. The torchlight made a tidal rush against flattened arches of milk grey stone. Parts of the walls were bricked, though the work was ancient and the brick face crumbling.

>[!quote] Son of a Witch
>At length, the narrow waterway runs into a wider channel that curves beneath a high ceiling of rock face supported here and there with beams and buttresses. On either side of the channel, padlocked doors are set flush into the stone walls. Sometimes the doors give out onto ledges or a path between cells; more often, just onto the water. The stench and the noise grow. Before long [you] pass grey-clothed laborers hauling buckets of supper one way, buckets of feces back.
###### Role this session 

###### Additional notes

<!--
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

`VIEW[### {npcs[0]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

`VIEW[### {npcs[1]}][text(renderMarkdown)]` 

###### Profile

###### Description

###### Role this session

###### Additional notes

`VIEW[### {npcs[2]}][text(renderMarkdown)]`

###### Profile

###### Description

###### Role this session

###### Additional notes

<!--
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
- [ ] **DC 10**: General Cherrystone was stationed in Quadling Country. The informant assumes that he was the one giving the orders during the burning of Bengda village, but he couldn't have participated because he was in Qhoyre at the time.
- [ ] **DC 15**: Cherrystone charged the village enormously large fines, knowing that they wouldn't be able to pay up, just so that he had an excuse to terrorize the village and make an example out its people in order to scare the nearby city of Qhoyre into cooperating with the Home Guard.
- [ ] **DC 20**: Some of the Bengdians that lead the revolt against the Home Guard were captured and taken alive by General Cherrystone.

###### For Merle
- [ ] **DC 10**: When Nor was being held in the Inner Ward, she once saw the Scarecrow being escorted to the Central Ward. Although it didn't appear to her that he was restrained, she felt as if he looked distressed. 
- [ ] **DC 15**: Nor tells Merle that an old rumor that circulated through the Southstairs resistance was that Shell orchestrated the "dethroning" of Scarecrow to facilitate his own takeover. 
- [ ] **DC 20**: Brrr tells Merle that the Scarecrow that sat upon the Throne in the Emerald Palace didn't feel like the same Scarecrow that he had journeyed with. Something about him had changed drastically.

###### For Scraps
- [ ] **DC 10**: A shady vendor in Market Square tells Scraps that ==*Glegg's Box of Mixed Magic*== is hidden away somewhere in ==the Vaults== 
- [ ] **DC 15**: Brrr tells Scraps that he doesn't buy the narrative that Mombi likes to tell about Tip She likes to portray Tip as a poor orphan boy that she adopted out of the kindness of her own heart, but Brrr thinks there is much more to the story. He shares his speculation that Mombi has placed a spell on Tip to keep him obedient.
- [ ] **DC 20**: Brr informs Scraps of the myth of Mombi's past. Stating that some people believe her to be much older than she lets on, and is truly the old Wicked Witch of the North that Glinda defeated more than 30 years ago.

###### For Siegfried
- [ ] DC 15: Meef is being held in ==the Cages==, on the outskirts of the ==Outer Ward== in the ==Prison District==.
- [ ] 

### For The Party

###### Mister Boss and Southstairs Entrance
- [x] Mister Boss tells the party of the two main entrances to Southstairs. The first is a lift in the city center and lowers you directly into the entrance to the prison district. The second is hidden in the Palace. It's common knowledge that there is a secret stairwell within the Palace walls, but most are unaware of where it is and where exactly it leads. 
- [x] **DC 10**: Mister Boss has it on good authority that the passage is located in the Wizard's old study and it leads straight to ==the Vaults==, a highly secure trove of the city's most valued secret relics and forbidden knowledge, hidden between the Market Square and the Under-Mayor's Ward. 
- [x] **DC 15**: Southstairs is known to have several secret entrances on the streets of Emerald City. But those who have been around for a while would know that before Southstairs was repurposed to hold the Wizard's worst enemies, it was part of the largest mining complex in Oz and employed most of the city's labor force. There's a forgotten entrance to the oldest part of Southstairs, an abandoned mine that hasn't operated in nearly a century. It is rumored to even have a lift, which might save the party some time, but who knows how safe it is. Mister Boss doesn't know how or even if it would lead to the prison district.

###### Mines
- The Coal Creek


###### Cullings
- [ ] **DC 10**: At first it was just reports from over in the Cages of Animals disappearing, then we started hearing claims that human prisoners were disappearing too. There were rumors of things happening in the Inner Ward, but there isn't much communication in and out of it since it is the maximum-security wing of the prison. Not too long after the rumors started though, Nor got evidence that the cullings had begun in the Outer Ward now, too.
- [ ] **DC 15**: People aren't just being transferred to another Ward during the cullings. Several prisoners have seen trails of blood that lead into the Center Ward, a place no prisoner has ever come back from.
- [ ] **DC 15**: A member of the party pickpockets a guard, obtaining a note that notifies the guard they're on "==*selection duty*==" tonight and they must report to the Central Ward at 2 AM.
- [ ] **DC 20**: A member of the party overhears a conversation between guards in which a woman asks another guard if he's on "==*selection duty*==" tonight. The guard confirms that he is and a second male guard asks if he's ever actually seen them in person. He says he hasn't, since he doesn't have clearance to enter the lair below the Central Ward, but sometimes he'll hear "chilling screams" coming from beneath the "==*prison layer*==".

###### Liir
- [ ] **DC 10**: Nor and Liir grew up in the Vinkus together; they were very close throughout childhood, right up until Nor was abducted.
- [ ] **DC 15**: Although he will deny it, Liir is Elphaba's son and he carries her same magical abilities, albeit they were still latent when Nor last saw him.
- [ ] **DC 20**: Brrr reveals that Nor and Liir are half siblings.

###### Dragons
- [ ] **DC 15**: A note found on one of the guards is signed by or mentions Menacier (Trism) bon Cavalish.
- [ ] **DC 25**: Brrr is in possession the page of the Grimmerie that Shell used to resurrect the dragons in Oz. The page is torn and singed around the edges

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
>>>  -  "1": Mister Boss, ally
>>>```
>>>- [ ] Complete
>>>___
>>>```encounter
>>>name: Open Tomb, The Undead
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": Skeleton
>>>  - "1": Shadow
>>>```
>>>- [ ] Complete
>>
>>>[!blank]
>>>```encounter
>>>name: Wizard's Study, Gargoyle
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": Gargoyle
>>>```
>>>- [ ] Complete
>>>___
>>>```encounter
>>>name: Southstairs, Watchmen
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "2": Clockwork Watchman
>>>```
>>>- [ ] Complete
>>
>>>[!blank]
>>>```encounter
>>>name: Southstairs, Prison Guards
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "2": Guard
>>>  - "1": Scout
>>>```
>>>- [ ] Complete
>>>___
>>>```encounter
>>>name: Southstairs, Death Dog
>>>players:
>>>  - Maylo
>>>  - Merle
>>>  - Scraps
>>>  - Siegfried
>>>creatures:
>>>  - "1": Death Dog
>>>```
>>>- [ ] Complete
>>

<br>

```encounter-table
name:
party: 
creatures:
  - 
```

## Potential Items  
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):items]`

### Locksmith's Wand
- [ ] Found
###### Importance
- Can be used to unlock one of the Vaults or a lock on a Cage
###### What?
- A magic wand with 1 charge of Knock and 1 charge of Arcane Lock
###### Where?
- 
###### How?
- 
###### Who?
- Merle Persimmon

### Glegg's Box of Mixed Magic
- [ ] Found
###### Importance
- Scraps is looking for it
###### What?
- 
###### Where?
- 
###### How?
- 
###### Who?
- Scraps


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
## What happened?


## Where did the party leave off?
- The party just woke up after a late night out drinking and watching the Clock of the Time Dragon's midnight adult show.
- They just discussed the two plans and decided their best chances were to infiltrate the Palace and find the secret stairway in the Wizard's study.
- Mister Boss reassures the party that he will do his best to assist them 
# Post Session Notes
