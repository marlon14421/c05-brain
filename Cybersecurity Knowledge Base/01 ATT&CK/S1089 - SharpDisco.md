---
type: "Malware"
source: MITRE ATT&CK
id: "S1089"
source_url: "https://attack.mitre.org/software/S1089"
created: "2023-09-26"
modified: "2025-04-16"
---
# S1089: SharpDisco

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1089  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SharpDisco](https://attack.mitre.org/software/S1089) is a dropper developed in C# that has been used by [MoustachedBouncer](https://attack.mitre.org/groups/G1019) since at least 2020 to load malicious plugins.(Citation: MoustachedBouncer ESET August 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1089](https://attack.mitre.org/software/S1089)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
