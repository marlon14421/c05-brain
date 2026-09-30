---
type: "Malware"
source: MITRE ATT&CK
id: "S9023"
source_url: "https://attack.mitre.org/software/S9023"
created: "2026-04-17"
modified: "2026-05-12"
---
# S9023: HiddenFace

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9023  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[HiddenFace](https://attack.mitre.org/software/S9023) is a modular backdoor developed and used exclusively by [MirrorFace](https://attack.mitre.org/groups/G1054) since at least 2021. [HiddenFace](https://attack.mitre.org/software/S9023) can communicate both actively and passively and has been used against political and academic targets.(Citation: JPCERT MirrorFace JUL 2024)(Citation: Trend Micro Earth Kasha NOV 2024)(Citation: Trend Micro Earth Kasha Updates APR 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9023](https://attack.mitre.org/software/S9023)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
