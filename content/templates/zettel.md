<%*
const title = await tp.system.prompt("Title?", null, true, false)
const permalink = await tp.system.prompt("permalink?", null, true, false)
await tp.file.rename(title);
-%>
---
title: <% title %>
permalink: <% permalink %>
draft: true
tags:
  - security
  - hacking
  - foundations
flashcards: true
status:
  - 🟥
aliases:
  - <% title %>
---
# <% title %>
## Notes 

### Overview

> [!summary] <% title %>
> 
> 
>> [!info] Sources 
>> 
>> 1. **source author**: ***source title*** [^1] 

### Definitions


### Examples

## Flashcards
> [!tip]- How To Use These Flashcards
> 
>> [!todo] Requirements
>> 1. Obsidian [^10] Installed
>> 2. Obsidian Vault Created
>> 3. Obsidian [^11] "***Spaced Repetition***" plugin installed
> 
>> [!todo] Instructions
>> 
>> Configure the "***Spaced Repetition***" Obsidian Plugin to have the following settings:
>> - *Separator for inline flashcards*: `;;`
>> - *Separator for inline **reversed** flashcards*: `;;;`

> [!info]- Flashcards
> 
## References
- {{link}}


[^10]: [Obsidian - Homepage](http://zotero.org/groups/5737020/items/5AMRCP64)
[^11]: [Spaced Repetition Obsidian Plugin - Github](http://zotero.org/groups/5737020/items/ZT6T6SKU)