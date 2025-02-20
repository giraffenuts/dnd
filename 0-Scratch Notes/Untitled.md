```encounter-table
name: Emerald Palace, Palace Guards
party: Oz
creatures: [2 Guard,Scout,Acolyte,"Mister Boss, ally"]
---
name: Wizard's Study, Gargoyle
party: Oz
creatures: [2 Gargoyle]
---
name: Southstairs, Watchmen
party: Oz
creatures: [3 Clockwork Watchman]
---
name: 
party: Oz
creatures: []
```

`BUTTON[insert-encounter,remove-encounter]`

```meta-bind-button
label: Remove Last Encounter
icon: minus
style: destructive
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: Remove the last encounter from the table
id: ""
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: "(^.*)---\n(.*\\]\n```)"
    replacement: "$1```"
    regexpFlags: gms

```

