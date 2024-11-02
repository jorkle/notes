---
title: Five Stages of Ethical Hacking
permalink: five-stages-of-ethical-hacking
draft: false
tags:
  - security
  - hacking
  - foundations
flashcards: true
status:
  - 🟩
aliases:
  - Five Stages of Ethical Hacking
---

## Notes



### Overview

> [!summary] Five Stages of Ethical Hacking
> 
>> [!info]- Diagram
>>  ```mermaid
>> graph TD
>> A(Reconnaissance ) 
>> A--> B(Scanning & Enumeration) 
>> B --> C(Gaining Access)
>> C --> D(Maintaining Access)
>> D --> E(Covering Tracks)
>> E --> A
>> ```
> 
> 1. Reconnaissance
> 2. Scanning & Enumeration
> 3. Gaining Access ("Exploitation")
> 4. Maintaining Access
> 5. Covering Tracks
>> [!info]- Sources 
>> 
>> 1. **TCM Security (YouTube)**: ***Ethical Hacking in 12 Hours - Full Course - Learn to Hack!*** [^1] 
---

### Definitions

> [!summary]- *Reconnaissance*
> The ***Reconnaissance*** phase of the ethical hacking life cycle is where the assessment team (attacker) attempts to gather as much information on the target as possible. This phase consists of both active and passive portions. The passive sub-component is where no direct connections are made to the target. It is debated amongst the security community whether browsing the target's public internet facing websites as a normal user would be considered active or not.
>> [!info]- Sources 
>> 
>> 1. **TCM Security (YouTube)**: ***Ethical Hacking in 12 Hours - Full Course - Learn to Hack!*** [^1] 

> [!summary]- *Scanning & Enumeration*
> The ***Scanning & Enumeration*** stage involves actively probing a target network or system to gather detailed information about its structure, services, and potential vulnerabilities. Techniques include port scanning, network mapping, and system identification. The goal is to build an accurate picture of the target to identify potential entry points for exploitation.
>> [!info]- Sources 
>> 
>> 1. **TCM Security (YouTube)**: ***Ethical Hacking in 12 Hours - Full Course - Learn to Hack!*** [^1] 

> [!summary]- *Gaining Access:*
> The ***Gaining Access*** stage is where the attacker (assessment team) exploits identified vulnerabilities to enter the target system or network. This might involve using techniques like password cracking, SQL injections, or exploiting software flaws. The primary goal is to obtain access to data or systems.
>> [!info]- Sources 
>> 
>> 1. **TCM Security (YouTube)**: ***Ethical Hacking in 12 Hours - Full Course - Learn to Hack!*** [^1] 

> [!summary]- *Maintaining Access*
>The ***Maintaining Access*** stage focuses on keeping the hacker's foothold within the target system or network over a period of time. Techniques used here often include installing backdoors, rootkits, or trojans to ensure re-entry and continuous access without detection. The hacker ensures they can come back as needed for further exploits or data exfiltration. This stage is crucial for long-term control and surveillance.
>> [!info]- Sources 
>> 
>> 1. **TCM Security (YouTube)**: ***Ethical Hacking in 12 Hours - Full Course - Learn to Hack!*** [^1] 

> [!summary]- *Covering Tracks*
>The ***Covering Tracks*** stage involves erasing evidence of the penetration test to restore the system to its original state. This includes removing any tools, scripts, or logs created during the test to ensure no traces are left behind. The goal is to prevent the penetration test from impacting the system's normal operations or exposing vulnerabilities inadvertently. It's all about leaving the system as secure and untouched as it was before the test.
>> [!info]- Sources 
>> 
>> 1. **TCM Security (YouTube)**: ***Ethical Hacking in 12 Hours - Full Course - Learn to Hack!*** [^1] 

---

### Examples

> [!info]- Reconnaissance
> **Examples**
>> [!example]- Active Reconnaissance
>> Going to the coffee shop across the road from the target organization's office to gather information on the target through social engineering employees on their lunch break.
>
>> [!example]- Passive Reconnaissance
>> Looking at photos on the target organization's LinkedIn page to find images of employees with their badges visible.

> [!info]- Scanning & Enumeration
> **Examples**
>> [!example]- Scanning & Enumeration
>> 
>> **TBA**

> [!info]- Gaining Access
> **Examples**
>> [!example]- Gaining Access
>> 
>> **TBA**

> [!info]- Maintaining Access
> **Examples**
>> [!example]- Maintaining Access
>> 
>> **TBA**

> [!info]- Covering Tracks
> **Examples**
>> [!example]- Covering Tracks
>> 
>> **TBA**

## Flashcards
> [!tip]- How To Use These Flashcards
> **Requirements**
> 1. Obsidian [^10] Installed
> 2. Obsidian Vault Created
> 3. Obsidian [^11] "***Spaced Repetition***" plugin installed
> ---
> **Instructions**
> 1. Configure the "***Spaced Repetition***" Obsidian Plugin to have the following settings:
> 	- *Separator for inline flashcards*: `;;`
> 	- *Separator for inline **reversed** flashcards*: `;;;`

> [!info]- Flashcards
> (reconnaissance): Define the **reconnaissance** phase of the ethical hacking cycle;;(**Define**): This stage involves gathering information about the target system or network. It includes passive information gathering techniques such as searching publicly available information, browsing websites, and examining DNS records. The goal is to collect as much information as possible to understand the target and identify potential entry points.
> (scanning & enumeration): Define the **scanning & enumeration** phase of the ethical hacking cycle;;;(**Define**): In this stage, the ethical hacker actively probes the target system or network to discover open ports, services, and vulnerabilities. Various tools and techniques are employed, such as port scanning, network mapping, and vulnerability scanning. This stage helps identify potential weaknesses that can be exploited.
> What are the **five** stages of ethical hacking?;;Reconnaissance, Scanning & Enumeration, Gaining Access ("Exploitation"), Maintaining Access, and Covering Tracks

## References


[^1]: [YouTube - Ethical Hacking in 12 Hours - Full Course - Learn to Hack! (Zotero)](http://zotero.org/groups/5737020/items/4MD46N3Y)
[^10]: [Obsidian - Homepage](http://zotero.org/groups/5737020/items/5AMRCP64)
[^11]: [Spaced Repetition Obsidian Plugin - Github](http://zotero.org/groups/5737020/items/ZT6T6SKU)