---
obsidianUIMode: preview
tags:
  - Category/Item
aliases: 
itemType: 
rarity: 
value: 
weight: 
source:
---

<% await tp.file.move("/2-Campaign/Items/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewItem");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Item Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


# Item Name
`VIEW[*{itemType}*][text(renderMarkdown)]`, `VIEW[*{rarity}*][text(renderMarkdown)]`  | `VIEW[{value}][text(renderMarkdown)]`,  `VIEW[{weight}][text(renderMarkdown)]` 

>###### Properties
>

>###### Description
>

*Source:* `VIEW[*{source}*][text(renderMarkdown)]`