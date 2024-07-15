---
aliases: [1on1]
---
Keeper's test

```dataview
TABLE 
round((date(now) - lastTalk[1]).days) AS "⏱ Days passed",
file.folder,
lastTalk[1] AS "Date"

FROM "People" 

WHERE 
directReport = true

SORT lastTalk[1] ASC
```

----


