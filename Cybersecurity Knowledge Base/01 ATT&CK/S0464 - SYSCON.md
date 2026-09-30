---
type: "Malware"
source: MITRE ATT&CK
id: "S0464"
source_url: "https://attack.mitre.org/software/S0464"
created: "2020-06-02"
modified: "2025-04-16"
---
# S0464: SYSCON

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0464  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SYSCON](https://attack.mitre.org/software/S0464) is a backdoor that has been in use since at least 2017 and has been associated with campaigns involving North Korean themes. [SYSCON](https://attack.mitre.org/software/S0464) has been delivered by the [CARROTBALL](https://attack.mitre.org/software/S0465) and [CARROTBAT](https://attack.mitre.org/software/S0462) droppers.(Citation: Unit 42 CARROTBAT November 2018)(Citation: Unit 42 CARROTBAT January 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0464](https://attack.mitre.org/software/S0464)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
