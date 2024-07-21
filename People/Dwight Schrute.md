---
directReport: true
aliases:
  - Dwayne
lastTalk: ""
---

> [!summary]-
> 
> Aspiration - Head of Product in 2 years
> 
> Growth needs:
> Sensitivity to other people's feelings and needs
>Showing appreciation for other people’s contributions
>Practicing patience and being in the present moment
>Giving space to others instead of micromanaging
>
>![[1on1 questions]]



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

We should open new [[DC]] location in [[Africa]] #nextOKR
Knows [[Pete Miller]], he has a reputation about delivering results but not caring about people
- [ ] I would benefit from knowing more about [[DNS]]. There is a great intro: https://howdns.works/ep1/ #toLearn

- [ ] Need to write a narrative #accountability ⏫ 📅 2024-08-21
- [ ] Amazing idea #toThink about for myself

