---
view-count: 2
---
# Characters
## All
>[!column|dataview no-title]
>>[!cards|dvl no-strong] 
>> <br>
>> 
>>```dataview
>>LIST WITHOUT ID file.link + "<br>" + file.mtime
>>FROM "2-Campaign/Characters/PCs"
>>WHERE file.name != "PCs" 
>>SORT file.name asc
>>```
<br>

## Popular
```dataviewjs 
const plugin = this.app.plugins.plugins["view-count"]; const cache = plugin.viewCountCache; const TIME_PERIOD = "7-days"; dv.table(["Characters", "Views this Week"], dv.pages('"2-Campaign/Characters/PCs"').where(p => p.file.name != "PCs").sort(p => cache.getTrendingWeight(p.file, TIME_PERIOD), "desc").map(p => [p.file.link, cache.getTrendingWeight(p.file, TIME_PERIOD)]) .slice(0,10) );
```