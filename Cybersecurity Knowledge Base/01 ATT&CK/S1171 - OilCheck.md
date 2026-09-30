---
type: "Malware"
source: MITRE ATT&CK
id: "S1171"
source_url: "https://attack.mitre.org/software/S1171"
created: "2024-11-26"
modified: "2024-11-27"
---
# S1171: OilCheck

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1171  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[OilCheck](https://attack.mitre.org/software/S1171) is a C#/.NET downloader that has been used by [OilRig](https://attack.mitre.org/groups/G0049) since at least 2022 including against targets in Israel. [OilCheck](https://attack.mitre.org/software/S1171) uses draft messages created in a shared email account for C2 communication.(Citation: ESET OilRig Downloaders DEC 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1171](https://attack.mitre.org/software/S1171)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
