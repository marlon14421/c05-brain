---
type: "Malware"
source: MITRE ATT&CK
id: "S0394"
source_url: "https://attack.mitre.org/software/S0394"
created: "2019-06-24"
modified: "2024-04-11"
---
# S0394: HiddenWasp

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0394  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[HiddenWasp](https://attack.mitre.org/software/S0394) is a Linux-based Trojan used to target systems for remote control. It comes in the form of a statically linked ELF binary with stdlibc++.(Citation: Intezer HiddenWasp Map 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0394](https://attack.mitre.org/software/S0394)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
