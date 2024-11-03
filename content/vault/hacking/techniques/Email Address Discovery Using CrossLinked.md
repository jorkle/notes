---
title: Email Address Discovery Using CrossLinked
permalink: crosslinked-email-discovery
draft: false
tags:
  - security
  - hacking
  - techniques
  - email
  - recon
  - osint
flashcards: false
status:
  - 🟩
aliases:
  - Email Address Discovery Using CrossLinked
---
# Email Address Discovery Using CrossLinked
## Notes 

### Overview

> [!quote] Email Address Discovery Using CrossLinked
> ***CrossLinked*** [^1] is a LinkedIn enumeration tool that uses search engine scraping to collect valid employee names from an organization. This technique provides accurate results without the use of API keys, credentials, or accessing LinkedIn directly!
> 
> ```bash
> # Usage, Company name must be as appears on LinkedIn
> 
> # Format email addresses
> crosslinked -f '{first}.{last}@domain.com' 'company_name'
> # Format with firstname as a single letter
> crosslinked -f '{f}.{last}@domain.com' 'company_name'
> 
> # Format as a domain account
> crosslinked -f 'DOMAIN\{first}{l}' 'company_name'
>```
>> [!info] Sources 
>> 
>> 1. **Pentest Everything (viperone)**: ***Discovering Email Addresses*** [^2] 

## References


[^1]: [m8sec/CrossLinked - Github](https://github.com/m8sec/CrossLinked)
[^2]: [http://zotero.org/groups/5737020/items/GZLNQ8ML](http://zotero.org/groups/5737020/items/GZLNQ8ML)
[^10]: [Obsidian - Homepage](http://zotero.org/groups/5737020/items/5AMRCP64)
[^11]: [Spaced Repetition Obsidian Plugin - Github](http://zotero.org/groups/5737020/items/ZT6T6SKU)