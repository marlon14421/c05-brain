---
type: "Malware"
source: MITRE ATT&CK
id: "S1076"
source_url: "https://attack.mitre.org/software/S1076"
created: "2023-05-19"
modified: "2025-04-16"
---
# S1076: QUIETCANARY

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1076  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[QUIETCANARY](https://attack.mitre.org/software/S1076) is a backdoor tool written in .NET that has been used since at least 2022 to gather and exfiltrate data from victim networks.(Citation: Mandiant Suspected Turla Campaign February 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1076](https://attack.mitre.org/software/S1076)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
