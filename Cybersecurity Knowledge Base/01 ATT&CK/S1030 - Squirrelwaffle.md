---
type: "Malware"
source: MITRE ATT&CK
id: "S1030"
source_url: "https://attack.mitre.org/software/S1030"
created: "2022-08-09"
modified: "2024-04-11"
---
# S1030: Squirrelwaffle

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1030  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Squirrelwaffle](https://attack.mitre.org/software/S1030) is a loader that was first seen in September 2021. It has been used in spam email campaigns to deliver additional malware such as [Cobalt Strike](https://attack.mitre.org/software/S0154) and the [QakBot](https://attack.mitre.org/software/S0650) banking trojan.(Citation: ZScaler Squirrelwaffle Sep 2021)(Citation: Netskope Squirrelwaffle Oct 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1030](https://attack.mitre.org/software/S1030)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
