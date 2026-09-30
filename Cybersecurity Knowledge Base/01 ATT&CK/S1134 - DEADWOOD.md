---
type: "Malware"
source: MITRE ATT&CK
id: "S1134"
source_url: "https://attack.mitre.org/software/S1134"
created: "2024-05-22"
modified: "2024-08-26"
---
# S1134: DEADWOOD

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1134  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DEADWOOD](https://attack.mitre.org/software/S1134) is wiper malware written in C++ using Boost libraries. [DEADWOOD](https://attack.mitre.org/software/S1134) was first observed in an unattributed wiping event in Saudi Arabia in 2019, and has since been incorporated into [Agrius](https://attack.mitre.org/groups/G1030) operations.(Citation: SentinelOne Agrius 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1134](https://attack.mitre.org/software/S1134)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
