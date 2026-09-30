---
type: "Malware"
source: MITRE ATT&CK
id: "S0618"
source_url: "https://attack.mitre.org/software/S0618"
created: "2021-06-04"
modified: "2024-04-11"
---
# S0618: FIVEHANDS

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0618  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[FIVEHANDS](https://attack.mitre.org/software/S0618) is a customized version of [DEATHRANSOM](https://attack.mitre.org/software/S0616) ransomware written in C++. [FIVEHANDS](https://attack.mitre.org/software/S0618) has been used since at least 2021, including in Ransomware-as-a-Service (RaaS) campaigns, sometimes along with [SombRAT](https://attack.mitre.org/software/S0615).(Citation: FireEye FiveHands April 2021)(Citation: NCC Group Fivehands June 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0618](https://attack.mitre.org/software/S0618)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
