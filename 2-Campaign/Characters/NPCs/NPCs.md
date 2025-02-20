---
characterFilter: ""
---
# Characters
## All
>[!column|dataview no-title]
> Search: `INPUT[text:characterFilter]`
>>[!cards|dvl no-strong] 
>> <br>
>> 
>>```dataview
>>LIST WITHOUT ID file.link + "<br>" + file.mtime
>>FROM "2-Campaign/Characters/NPCs"
>>WHERE contains(file.name, this.characterFilter) OR contains(file.aliases, this.characterFilter) AND file.name != "NPCs" 
>>SORT file.name asc
>>```
<br>

## Popular
```dataviewjs 
const plugin = this.app.plugins.plugins["view-count"]; const cache = plugin.viewCountCache; const TIME_PERIOD = "7-days"; dv.table(["Characters", "Views this Week"], dv.pages('"2-Campaign/Characters/NPCs"').where(p => p.file.name != "NPCs").sort(p => cache.getTrendingWeight(p.file, TIME_PERIOD), "desc").map(p => [p.file.link, cache.getTrendingWeight(p.file, TIME_PERIOD)]) .slice(0,10) );
```