---
type: "Malware"
source: MITRE ATT&CK
id: "S1085"
source_url: "https://attack.mitre.org/software/S1085"
created: "2023-09-05"
modified: "2025-10-22"
---
# S1085: Sardonic

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1085  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Sardonic](https://attack.mitre.org/software/S1085) is a backdoor written in C and C++ that is known to be used by [FIN8](https://attack.mitre.org/groups/G0061), as early as August 2021 to target a financial institution in the United States. [Sardonic](https://attack.mitre.org/software/S1085) has a plugin system that can load specially made DLLs and execute their functions.(Citation: Bitdefender Sardonic Aug 2021)(Citation: Symantec FIN8 Jul 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1085](https://attack.mitre.org/software/S1085)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
