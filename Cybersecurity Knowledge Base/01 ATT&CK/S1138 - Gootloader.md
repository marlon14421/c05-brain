---
type: "Malware"
source: MITRE ATT&CK
id: "S1138"
source_url: "https://attack.mitre.org/software/S1138"
created: "2024-05-28"
modified: "2024-06-19"
---
# S1138: Gootloader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1138  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Gootloader](https://attack.mitre.org/software/S1138) is a Javascript-based infection framework that has been used since at least 2020 as a delivery method for the Gootkit banking trojan, [Cobalt Strike](https://attack.mitre.org/software/S0154), [REvil](https://attack.mitre.org/software/S0496), and others. [Gootloader](https://attack.mitre.org/software/S1138) operates on an "Initial Access as a Service" model and has leveraged [SEO Poisoning](https://attack.mitre.org/techniques/T1608/006) to provide access to entities in multiple sectors worldwide including financial, military, automotive, pharmaceutical, and energy.(Citation: Sophos Gootloader)(Citation: SentinelOne Gootloader June 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1138](https://attack.mitre.org/software/S1138)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
