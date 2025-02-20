---
locationHeader: "`VIEW[### {locations[]}][text(renderMarkdown)]`"
---
```meta-bind-js-view
{locationCount} as count
save to {locationHeader}
---
const str = 
`\`VIEW[### {locations[${context.bound.count}]}][text(renderMarkdown)]\``;
return engine.markdown.create(str)
```



*Indirect description:* 

*Observational description:* 


```meta-bind-button
label: Insert another location
icon: map-pin-plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: "insert-location"
hidden: false
actions:
- type: "replaceSelf"
  replacement: "z_Templates/5_Meta Bind/Button - Insert location.md"
  templater: true
- type: updateMetadata
  bindTarget: locationCount
  evaluate: true
  value: x + 1
```