---
type: "Malware"
source: MITRE ATT&CK
id: "S9026"
source_url: "https://attack.mitre.org/software/S9026"
created: "2026-04-17"
modified: "2026-05-12"
---
# S9026: ROAMINGHOUSE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9026  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ROAMINGHOUSE](https://attack.mitre.org/software/S9026) is a dropper malware used by [MirrorFace](https://attack.mitre.org/groups/G1054) to extract and execute embedded payloads including [UPPERCUT](https://attack.mitre.org/software/S0275) components.(Citation: Trend Micro Earth Kasha Updates APR 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9026](https://attack.mitre.org/software/S9026)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
