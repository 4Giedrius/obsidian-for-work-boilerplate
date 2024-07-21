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

![[1on1 questions]]

[1-1 Template and Instructions](https://docs.google.com/document/d/1j7ZNWTh9ClS0PZHrpZXGk879pv9LXDWt6sjaq1uA-zA/edit)

