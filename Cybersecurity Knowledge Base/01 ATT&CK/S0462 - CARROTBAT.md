---
type: "Malware"
source: MITRE ATT&CK
id: "S0462"
source_url: "https://attack.mitre.org/software/S0462"
created: "2020-06-02"
modified: "2024-04-11"
---
# S0462: CARROTBAT

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0462  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[CARROTBAT](https://attack.mitre.org/software/S0462) is a customized dropper that has been in use since at least 2017. [CARROTBAT](https://attack.mitre.org/software/S0462) has been used to install [SYSCON](https://attack.mitre.org/software/S0464) and has infrastructure overlap with [KONNI](https://attack.mitre.org/software/S0356).(Citation: Unit 42 CARROTBAT November 2018)(Citation: Unit 42 CARROTBAT January 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0462](https://attack.mitre.org/software/S0462)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
