---
type: "Malware"
source: MITRE ATT&CK
id: "S1074"
source_url: "https://attack.mitre.org/software/S1074"
created: "2023-05-16"
modified: "2023-09-29"
---
# S1074: ANDROMEDA

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1074  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ANDROMEDA](https://attack.mitre.org/software/S1074) is commodity malware that was widespread in the early 2010's and continues to be observed in infections across a wide variety of industries. During the 2022 [C0026](https://attack.mitre.org/campaigns/C0026) campaign, threat actors re-registered expired [ANDROMEDA](https://attack.mitre.org/software/S1074) C2 domains to spread malware to select targets in Ukraine.(Citation: Mandiant Suspected Turla Campaign February 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1074](https://attack.mitre.org/software/S1074)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
