---
type: "Malware"
source: MITRE ATT&CK
id: "S1212"
source_url: "https://attack.mitre.org/software/S1212"
created: "2025-03-17"
modified: "2025-03-27"
---
# S1212: RansomHub

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1212  
**Platforms:** Linux, Windows  
**Tactics:** Not specified

## Source description

[RansomHub](https://attack.mitre.org/software/S1212) is a ransomware-as-a-service (RaaS) offering with Windows, ESXi, Linux, and FreeBSD versions that has been in use since at least 2024 to target organizations in multiple sectors globally. [RansomHub](https://attack.mitre.org/software/S1212) operators may have purchased and rebranded resources from Knight (formerly Cyclops) Ransomware which shares infrastructure, feature, and code overlaps with [RansomHub](https://attack.mitre.org/software/S1212).(Citation: CISA RansomHub AUG 2024)(Citation: Group-IB RansomHub FEB 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1212](https://attack.mitre.org/software/S1212)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
