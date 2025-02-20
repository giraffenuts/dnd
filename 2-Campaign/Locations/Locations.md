---
tags:
  - homepage
locationFilter: ""
---
# Locations
## All
>[!column|dataview 2]+ All Locations
> Search: `INPUT[text:locationFilter]`
> 
>>[!cards|dvl no-strong] 
>> <br>
>>
>>```dataview
LIST WITHOUT ID file.link + "<br>" + file.mtime
FROM "2-Campaign/Locations"
WHERE contains(file.name, this.locationFilter) OR contains(file.aliases, this.locationFilter) AND file.name != "Locations"
SORT file.name asc
>>```
## Popular
>[!column|no-title]
>>[!blank]
>>```dataview 
TABLE WITHOUT ID 
file.link AS "Locations",
view-count AS "Days Viewed"
FROM "2-Campaign/Locations"
WHERE file.name != "Locations"
SORT view-count DESC
LIMIT 10
>>```
>
>>[!blank]
>>```dataviewjs 
const plugin = this.app.plugins.plugins["view-count"]; const cache = plugin.viewCountCache; const TIME_PERIOD = "7-days"; dv.table(["Locations", "Views this Week"], dv.pages('"2-Campaign/Locations"').where(p => p.file.name != "Locations").sort(p => cache.getTrendingWeight(p.file, TIME_PERIOD), "desc").map(p => [p.file.link, cache.getTrendingWeight(p.file, TIME_PERIOD)]) .slice(0,10) );
>>```

## Recently Edited
> [!cards|dataview]
> ```dataview
> TABLE WITHOUT ID
> 	"![|sban cover hmicro](" + image + ")" as Image,
> 	"**"+ file.link + "**" AS "Column Name",
> 	file.mtime AS "Modified"
> FROM "2-Campaign/Locations"
> WHERE file.name != "Locations"
> SORT file.mtime desc
> LIMIT 9
> ```