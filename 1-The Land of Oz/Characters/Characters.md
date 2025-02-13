---
characterFilter: ""
---
# Characters
## All
>[!column|dataview 3]+ All Characters
> Search: `INPUT[text:characterFilter]`
> 
>>[!cards|dvl no-strong] 
>> <br>
>>
>>```dataview
LIST WITHOUT ID file.link + "<br>" + file.mtime
FROM "1-The Land of Oz/Characters"
WHERE contains(file.name, this.characterFilter) OR contains(file.aliases, this.characterFilter) AND file.name != "Characters" 
SORT file.name asc
>>```
## Popular
>[!column|no-title]
>>[!blank]
>>```dataview 
TABLE WITHOUT ID 
file.link AS "Characters",
view-count AS "Days Viewed"
FROM "1-The Land of Oz/Characters"
WHERE file.name != "Characters"
SORT view-count DESC
LIMIT 10
>>```
>
>>[!blank]
>>```dataviewjs 
const plugin = this.app.plugins.plugins["view-count"]; const cache = plugin.viewCountCache; const TIME_PERIOD = "7-days"; dv.table(["Characters", "Views this Week"], dv.pages('"1-The Land of Oz/Characters"').where(p => p.file.name != "Characters").sort(p => cache.getTrendingWeight(p.file, TIME_PERIOD), "desc").map(p => [p.file.link, cache.getTrendingWeight(p.file, TIME_PERIOD)]) .slice(0,10) );
>>```

## Recently Edited
> [!cards|dataview]
> ```dataview
> TABLE WITHOUT ID
> 	"![|sban cover hmicro](" + image + ")" as Image,
> 	"**"+ file.link + "**" AS "Column Name",
> 	file.mtime AS "Modified"
> FROM "1-The Land of Oz/Characters"
> WHERE file.name != "Characters"
> SORT file.mtime desc
> LIMIT 9
> ```
