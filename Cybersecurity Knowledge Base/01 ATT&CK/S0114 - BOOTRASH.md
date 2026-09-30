---
type: "Malware"
source: MITRE ATT&CK
id: "S0114"
source_url: "https://attack.mitre.org/software/S0114"
created: "2017-05-31"
modified: "2024-11-17"
---
# S0114: BOOTRASH

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0114  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[BOOTRASH](https://attack.mitre.org/software/S0114) is a [Bootkit](https://attack.mitre.org/techniques/T1542/003) that targets Windows operating systems. It has been used by threat actors that target the financial sector.(Citation: Mandiant M Trends 2016)(Citation: FireEye Bootkits)(Citation: FireEye BOOTRASH SANS)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0114](https://attack.mitre.org/software/S0114)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
