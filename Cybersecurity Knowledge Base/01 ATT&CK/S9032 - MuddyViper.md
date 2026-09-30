---
type: "Malware"
source: MITRE ATT&CK
id: "S9032"
source_url: "https://attack.mitre.org/software/S9032"
created: "2026-04-20"
modified: "2026-04-23"
---
# S9032: MuddyViper

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9032  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[MuddyViper](https://attack.mitre.org/software/S9032) is custom backdoor written in C and C++ used by [MuddyWater](https://attack.mitre.org/groups/G0069) for command and control (C2) communications and persistence. [MuddyViper](https://attack.mitre.org/software/S9032) is loaded by [Fooder](https://attack.mitre.org/software/S9033) and sends frequent messages to the C2 server.(Citation: ESET_MuddyWater_Dec2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9032](https://attack.mitre.org/software/S9032)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
