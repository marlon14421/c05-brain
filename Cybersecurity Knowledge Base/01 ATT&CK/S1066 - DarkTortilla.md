---
type: "Malware"
source: MITRE ATT&CK
id: "S1066"
source_url: "https://attack.mitre.org/software/S1066"
created: "2023-02-16"
modified: "2025-04-16"
---
# S1066: DarkTortilla

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1066  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DarkTortilla](https://attack.mitre.org/software/S1066) is a highly configurable .NET-based crypter that has been possibly active since at least August 2015. [DarkTortilla](https://attack.mitre.org/software/S1066) has been used to deliver popular information stealers, RATs, and payloads such as [Agent Tesla](https://attack.mitre.org/software/S0331), AsyncRat, [NanoCore](https://attack.mitre.org/software/S0336), RedLine, [Cobalt Strike](https://attack.mitre.org/software/S0154), and Metasploit.(Citation: Secureworks DarkTortilla Aug 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1066](https://attack.mitre.org/software/S1066)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
