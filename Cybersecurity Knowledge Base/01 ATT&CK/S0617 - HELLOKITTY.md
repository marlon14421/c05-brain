---
type: "Malware"
source: MITRE ATT&CK
id: "S0617"
source_url: "https://attack.mitre.org/software/S0617"
created: "2021-06-03"
modified: "2025-04-25"
---
# S0617: HELLOKITTY

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0617  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[HELLOKITTY](https://attack.mitre.org/software/S0617) is a ransomware written in C++ that shares similar code structure and functionality with [DEATHRANSOM](https://attack.mitre.org/software/S0616) and [FIVEHANDS](https://attack.mitre.org/software/S0618). [HELLOKITTY](https://attack.mitre.org/software/S0617) has been used since at least 2020, targets have included a Polish video game developer and a Brazilian electric power company.(Citation: FireEye FiveHands April 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0617](https://attack.mitre.org/software/S0617)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
