---
type: "Malware"
source: MITRE ATT&CK
id: "S1133"
source_url: "https://attack.mitre.org/software/S1133"
created: "2024-05-22"
modified: "2024-08-29"
---
# S1133: Apostle

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1133  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Apostle](https://attack.mitre.org/software/S1133) is malware that has functioned as both a wiper and, in more recent versions, as ransomware. [Apostle](https://attack.mitre.org/software/S1133) is written in .NET and shares various programming and functional overlaps with [IPsec Helper](https://attack.mitre.org/software/S1132).(Citation: SentinelOne Agrius 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1133](https://attack.mitre.org/software/S1133)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
