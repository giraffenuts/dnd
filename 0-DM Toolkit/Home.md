---
creatureSearch: ""
characterFilter: ""
---
# Frequented Notes

# Buttons
###### Combat: `BUTTON[open-initiative-tracker,build-new-encounter]`

###### Characters: `BUTTON[new-npc,new-pc]`

###### Locations: `BUTTON[new-location]`

###### Items: `BUTTON[new-item]`

###### Sessions: `BUTTON[new-session-notes]` 

# Characters

>[!column|dataview 3]+ Search Characters
> Search: `INPUT[text:characterFilter]`
> 
>>[!cards|dvl no-strong] 
>> <br>
>>
>>```dataview
>>LIST WITHOUT ID file.link + "<br>" + file.mtime
>>FROM "1-The Land of Oz/Characters" OR "2-Campaign/Characters"
>>WHERE contains(file.name, this.characterFilter) OR contains(file.aliases, this.characterFilter) AND file.name != "Characters" AND file.name != "NPCs" AND file.name != "PCs"
>>SORT file.name asc
>>LIMIT 6
>>```



```dataviewjs
const bestiary = FantasyStatblocks.getBestiary();
const creatures = bestiary.values();
const monstersAsDvArray = dv.array(Array.from(bestiary.values())).filter(m => m.name).where(m => m.name.toLowerCase().contains('mage'))

dv.table(["Name", "HP", "AC", "CR"], monstersAsDvArray.map((monster) => [dv.fileLink(monster.name), monster.hp, monster.ac, monster.cr]))
```