<%*
// Prompt user for header name
const headerName = await tp.system.prompt("Enter NPC Name");
const uniqueId = `npc-section-${Date.now()}`; // Unique identifier
-%>
### <% headerName %> 

###### Profile

###### Description

###### Role this session

###### Additional notes
<!-- last-npc-id -->
```meta-bind-button
label: Insert NPC description
icon: plus
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: regexpReplaceInNote
    regexp: "<!-- last-npc-id -->\n"
    replacement: "\n"
    regexpFlags: g
  - type: replaceSelf
    replacement: "z_Templates/5_Meta Bind/Template Button - Insert NPC Description.md"
    templater: true
```