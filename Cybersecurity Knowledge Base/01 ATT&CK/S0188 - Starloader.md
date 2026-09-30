---
type: "Malware"
source: MITRE ATT&CK
id: "S0188"
source_url: "https://attack.mitre.org/software/S0188"
created: "2018-01-16"
modified: "2025-04-25"
---
# S0188: Starloader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0188  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Starloader](https://attack.mitre.org/software/S0188) is a loader component that has been observed loading [Felismus](https://attack.mitre.org/software/S0171) and associated tools. (Citation: Symantec Sowbug Nov 2017)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0188](https://attack.mitre.org/software/S0188)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
