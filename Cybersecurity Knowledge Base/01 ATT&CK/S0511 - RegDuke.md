---
type: "Malware"
source: MITRE ATT&CK
id: "S0511"
source_url: "https://attack.mitre.org/software/S0511"
created: "2020-09-23"
modified: "2025-04-16"
---
# S0511: RegDuke

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0511  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[RegDuke](https://attack.mitre.org/software/S0511) is a first stage implant written in .NET and used by [APT29](https://attack.mitre.org/groups/G0016) since at least 2017. [RegDuke](https://attack.mitre.org/software/S0511) has been used to control a compromised machine when control of other implants on the machine was lost.(Citation: ESET Dukes October 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0511](https://attack.mitre.org/software/S0511)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
