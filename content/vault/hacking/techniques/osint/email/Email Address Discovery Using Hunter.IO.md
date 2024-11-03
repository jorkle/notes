---
title: Email Address Discovery Using Hunter.IO
description: "How to discover email addresses using Hunter.IO"
permalink: hunterio-email-osint-technique
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
  - Email Address Discovery Using Hunter.IO
---
# Email Discovery Using Hunter.IO

## Notes 

### Overview

> [!quote] Email Address Discovery Using Hunter.IO
> ***Hunter.io*** [^1] is an web service that is used for finding email addresses and contacts from businesses. The most common option is to perform a domain search.
> 
> Hunter.io will return all found addresses and sources for the address for the searched domain. Hunter.io will also present the most common email pattern for the domain in question as shown below.
> 
> 
> ![[../../../../../attachments/Pasted image 20241103045111.png]]
> 
> This can also be used to filter between generic email addresses such as info@microsoft.com and personal addresses such as EricHolk@microsoft.com (As shown above).
>
> The results can also be further filtered by department such as HR or Management as shown above.
>
> Look at an individual results we are able to expanded the sources to see where Hunter.io pulled this information from.
> 
> ![[../../../../../attachments/Pasted image 20241103045231.png]]
> 
> Confirmed valid addresses are marked with a tick and green shield icon. However, it is also possible to perform manual verification on an address to see if it really exists using Hunter.io
>
> The manual verification method will attempt to verify the mail address by querying the MX records for that domain.
> 
> ![[../../../../../attachments/Pasted image 20241103045314.png]]
> 
>> [!info] Sources 
>> 
>> 1. **Pentest Everything (viperone)**: ***Discovering Email Addresses*** [^2] 


## References


[^1]: [Hunter.IO - Homepage](https://hunter.io/)
[^2]: [http://zotero.org/groups/5737020/items/GZLNQ8ML](http://zotero.org/groups/5737020/items/GZLNQ8ML)
[^10]: [Obsidian - Homepage](http://zotero.org/groups/5737020/items/5AMRCP64)
[^11]: [Spaced Repetition Obsidian Plugin - Github](http://zotero.org/groups/5737020/items/ZT6T6SKU)