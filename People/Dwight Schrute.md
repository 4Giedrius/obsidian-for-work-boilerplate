---
directReport: true
aliases:
  - Dwayne
lastTalk: ""
---

```dataviewjs
function callout(text, type) {
    const allText = `> [!${type}]\n` + text;
    const lines = allText.split('\n');
    return lines.join('\n> ') + '\n'
}

const query = `
not done
path includes ${dv.current().file.path}
description includes #accountability 
# you can add any number of extra Tasks instructions, for example:
group by heading
`;

dv.paragraph(callout('```tasks\n' + query + '\n```', 'Accountability'));
```




(lastTalk:: 2024-07-15)
This is a note about 

- [ ] Need to write a narrative #accountability ⏫ 📅 2024-08-21
- [ ] Amazing idea #toThink about for myself