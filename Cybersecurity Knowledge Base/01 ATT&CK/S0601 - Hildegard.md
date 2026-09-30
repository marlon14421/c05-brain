---
type: "Malware"
source: MITRE ATT&CK
id: "S0601"
source_url: "https://attack.mitre.org/software/S0601"
created: "2021-04-07"
modified: "2024-04-11"
---
# S0601: Hildegard

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0601  
**Platforms:** Linux, Containers, IaaS  
**Tactics:** Not specified

## Source description

[Hildegard](https://attack.mitre.org/software/S0601) is malware that targets misconfigured kubelets for initial access and runs cryptocurrency miner operations. The malware was first observed in January 2021. The TeamTNT activity group is believed to be behind [Hildegard](https://attack.mitre.org/software/S0601). (Citation: Unit 42 Hildegard Malware)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0601](https://attack.mitre.org/software/S0601)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
