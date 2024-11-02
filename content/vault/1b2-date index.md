---
title: Date Index
draft: true
permalink: data-index
link: "[[1b - indexes]]"
tags:
  - note-system
flashcards: false
status:
  - 🟩
aliases:
  - date index
---

# date index

## content

### date created
```dataview
TABLE WITHOUT ID (date-created + "(" + length(rows.file.link) + ")") AS Dates, (rows.file.link) AS Files
FROM "zettelkasten"
WHERE file.cday
FLATTEN file.cday AS date-created
GROUP BY date-created
SORT length(rows.file.link) DESC
```

---

### date modified
```dataview
TABLE WITHOUT ID (date-modified + "(" + length(rows.file.link) + ")") AS Dates, (rows.file.link) AS Files
FROM "zettelkasten"
WHERE file.mday
FLATTEN file.mday AS date-modified
GROUP BY date-modified
SORT length(rows.file.link) DESC
```


## references
- [[1b - indexes]]