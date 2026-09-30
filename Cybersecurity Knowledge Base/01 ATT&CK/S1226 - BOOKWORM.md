---
type: "Malware"
source: MITRE ATT&CK
id: "S1226"
source_url: "https://attack.mitre.org/software/S1226"
created: "2025-07-21"
modified: "2025-10-21"
---
# S1226: BOOKWORM

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1226  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[BOOKWORM](https://attack.mitre.org/software/S1226) is a modular trojan known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2015. [BOOKWORM](https://attack.mitre.org/software/S1226) was later updated in late 2021 and the fall of 2022 to launch shellcode represented as UUID parameters. (Citation: Broadcom)(Citation: Unit42 Bookworm Nov2015)(Citation: Palo Alto Networks, Unit 42)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1226](https://attack.mitre.org/software/S1226)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
