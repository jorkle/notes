---
title: Tag Index
draft: true
permalink: tag-index
link: "[[1b - indexes]]"
tags:
  - note-system
flashcards: false
status:
  - 🟩
---

# tag index

## content

```dataview
TABLE WITHOUT ID (tag + "(" + length(rows.file.link) + ")") AS Tags, (rows.file.link) AS Files
FROM "zettelkasten"
WHERE file.tags
FLATTEN file.tags AS tag
GROUP BY tag
SORT length(rows.file.link) DESC
```

## references
- [[1b - indexes|indexes]]
- [[1a - keyboard shortcut reference]]