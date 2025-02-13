---
characterFilter: ""
view-count: 5
---
# Characters
## All
>[!column|dataview 2]+ All Characters
> Search: `INPUT[text:characterFilter]`
> 
>>[!cards|dvl no-strong] 
>> <br>
>>
>>```dataview
LIST WITHOUT ID file.link + "<br>" + file.mtime
FROM "2-Campaign/Characters"
WHERE contains(file.name, this.characterFilter) OR contains(file.aliases, this.characterFilter) AND file.name != "Characters" AND file.name != "PCs" AND file.name != "NPCs" 
SORT file.name asc
>>```
## Popular
>[!column|no-title]
>>[!blank]
>>```dataview 
TABLE WITHOUT ID 
file.link AS "Characters",
view-count AS "Days Viewed"
FROM "2-Campaign/Characters"
WHERE file.name != "Characters" AND file.name != "NPCs" AND file.name != "PCs"
SORT view-count DESC
LIMIT 10
>>```
>
>>[!blank]
>>```dataviewjs 
const plugin = this.app.plugins.plugins["view-count"]; const cache = plugin.viewCountCache; const TIME_PERIOD = "7-days"; dv.table(["Characters", "Views this Week"], dv.pages('"2-Campaign/Characters"').where(p => p.file.name != "Characters").where(p => p.file.name != "NPCs").where(p => p.file.name != "PCs").sort(p => cache.getTrendingWeight(p.file, TIME_PERIOD), "desc").map(p => [p.file.link, cache.getTrendingWeight(p.file, TIME_PERIOD)]) .slice(0,10) );
>>```

## Recently Edited
> [!cards|dataview]
> ```dataview
> TABLE WITHOUT ID
> 	"![|sban cover hmicro](" + image + ")" as Image,
> 	"**"+ file.link + "**" AS "Column Name",
> 	file.mtime AS "Modified"
> FROM "2-Campaign/Characters"
> WHERE file.name != "Characters" AND file.name != "PCs" AND file.name != "NPCs"
> SORT file.mtime desc
> LIMIT 9
> ```
