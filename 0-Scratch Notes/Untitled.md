```encounter-table
name: 
party: Oz
creatures:
  - 
```

```meta-bind-button
label: Insert New Encounter
icon: plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: Insert another encounter into the table
id: ""
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: "[`]{3}encounter-table\n([^`]*)[`]{3}"
    replacement: "```encounter-table\nname: \nparty: Oz\ncreatures:\n  - \n---\n$1```"
    regexpFlags: gm
```

```meta-bind-button
label: Remove Last Encounter
icon: plus
style: destructive
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: Remove the last encounter from the table
id: ""
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: "([`]{3}encounter-table)\nname:.*\nparty:.*\ncreatures:\n[\\s\\S]*?---"
    replacement: "$1"
    regexpFlags: gm
```