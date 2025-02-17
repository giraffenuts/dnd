---
creatureSearch: ""
characterFilter: ""
locationFilter: South
---
> [!cards|dataview]
> ```dataview
> TABLE WITHOUT ID
> 	"![|sban cover hmicro](" + image + ")" as Image,
> 	"**"+ file.link + "**" AS "Column Name"
> FROM #homepage
> SORT file.name asc
> ```

# Recent
## Session Notes

> [!cards|dataview]
> ```dataview
> TABLE WITHOUT ID
> 	"![|sban cover hmicro](" + image + ")" as Image,
> 	"**"+ file.link + "**" AS "Column Name",
> 	file.mtime AS "Modified"
> FROM "2-Campaign/Sessions"
> SORT file.mtime desc
> LIMIT 2
> ```

# Buttons

>[!column| 2]
>>[!blank] 
>>###### Characters: `BUTTON[new-npc,new-pc]`
>>###### Locations: `BUTTON[new-location]`
>>###### Items: `BUTTON[new-item]`
>
>>[!blank] 
>>###### Combat: `BUTTON[open-initiative-tracker,build-new-encounter]`
>>###### Sessions: `BUTTON[new-session-notes]` 


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
>>WHERE contains(lower(file.name), lower(this.characterFilter)) OR contains(lower(file.aliases), lower(this.characterFilter)) AND file.name != "Characters" AND file.name != "NPCs" AND file.name != "PCs"
>>SORT file.name asc
>>LIMIT 6
>>```

# Locations

>[!column|dataview 3]+ Search Locations
> Search: `INPUT[text:locationFilter]`
> 
>>[!cards|dvl no-strong] 
>> <br>
>>
>>```dataview
>>LIST WITHOUT ID file.link + "<br>" + file.mtime
>>FROM "1-The Land of Oz/Places" OR "2-Campaign/Locations"
>>WHERE contains(lower(file.name), lower(this.locationFilter)) OR contains(lower(file.aliases), lower(this.locationFilter)) AND file.name != "Locations" AND file.name != "Places"
>>SORT file.name asc
>>LIMIT 6
>>```


```dataviewjs
const bestiary = FantasyStatblocks.getBestiary();
const creatures = bestiary.values();
const monstersAsDvArray = dv.array(Array.from(bestiary.values())).filter(m => m.name).where(m => m.name.toLowerCase().contains('mage'))

dv.table(["Name", "HP", "AC", "CR"], monstersAsDvArray.map((monster) => [dv.fileLink(monster.name), monster.hp, monster.ac, monster.cr]))
```