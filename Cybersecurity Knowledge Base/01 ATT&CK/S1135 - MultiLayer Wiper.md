---
type: "Malware"
source: MITRE ATT&CK
id: "S1135"
source_url: "https://attack.mitre.org/software/S1135"
created: "2024-05-22"
modified: "2024-08-29"
---
# S1135: MultiLayer Wiper

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1135  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[MultiLayer Wiper](https://attack.mitre.org/software/S1135) is wiper malware written in .NET associated with [Agrius](https://attack.mitre.org/groups/G1030) operations. Observed samples of [MultiLayer Wiper](https://attack.mitre.org/software/S1135) have an anomalous, future compilation date suggesting possible metadata manipulation.(Citation: Unit42 Agrius 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1135](https://attack.mitre.org/software/S1135)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
