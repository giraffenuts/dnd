---
listOptions:
  - "1"
  - "2"
  - "3"
  - "4"
listSelected: 
selected: 1
---

Options: `INPUT[inlineList:listOptions]`

```meta-bind-js-view
{listOptions} as options
{listSelected} as selected
---
const options = context.bound.options.map(x => `option(${x})`).join(", ");
const str = `\`INPUT[inlineSelect(${options}):selected]\``;

return engine.markdown.create(str);
```
