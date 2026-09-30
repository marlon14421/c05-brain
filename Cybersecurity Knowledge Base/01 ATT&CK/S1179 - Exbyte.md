---
type: "Malware"
source: MITRE ATT&CK
id: "S1179"
source_url: "https://attack.mitre.org/software/S1179"
created: "2024-12-17"
modified: "2025-03-09"
---
# S1179: Exbyte

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1179  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Exbyte](https://attack.mitre.org/software/S1179) is an exfiltration tool written in Go that is uniquely associated with [BlackByte](https://attack.mitre.org/groups/G1043) operations. Observed since 2022, [Exbyte](https://attack.mitre.org/software/S1179) transfers collected files to online file sharing and hosting services.(Citation: Symantec BlackByte 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1179](https://attack.mitre.org/software/S1179)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
