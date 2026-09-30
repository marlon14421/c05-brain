---
type: "Malware"
source: MITRE ATT&CK
id: "S1158"
source_url: "https://attack.mitre.org/software/S1158"
created: "2024-09-16"
modified: "2024-09-21"
---
# S1158: DUSTPAN

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1158  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DUSTPAN](https://attack.mitre.org/software/S1158) is an in-memory dropper written in C/C++ used by [APT41](https://attack.mitre.org/groups/G0096) since 2021 that decrypts and executes an embedded payload.(Citation: Google Cloud APT41 2024)(Citation: Google Cloud APT41 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1158](https://attack.mitre.org/software/S1158)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
