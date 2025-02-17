---
obsidianUIMode: preview
tags:
  - Category/Item
aliases: 
SourceType: Magic Item
damageDice: 1d6
damageType: piercing
---

<% await tp.file.move("/2-Campaign/Items/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewMagicItem");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Item Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


# Item Name
*Item type, rarity*  

- **Damage**: `VIEW[```dice: {damageDice}```][text(renderMarkdown)]` `VIEW[{damageType}][text]`
- **Properties**: 
- **Cost**: ⏤
- **Weight**: 2.0 lbs.

Description

*Source: SourceName*