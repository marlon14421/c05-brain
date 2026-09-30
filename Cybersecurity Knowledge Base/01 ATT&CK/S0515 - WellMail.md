---
type: "Malware"
source: MITRE ATT&CK
id: "S0515"
source_url: "https://attack.mitre.org/software/S0515"
created: "2020-09-29"
modified: "2025-04-25"
---
# S0515: WellMail

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0515  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[WellMail](https://attack.mitre.org/software/S0515) is a lightweight malware written in Golang used by [APT29](https://attack.mitre.org/groups/G0016), similar in design and structure to [WellMess](https://attack.mitre.org/software/S0514).(Citation: CISA WellMail July 2020)(Citation: NCSC APT29 July 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0515](https://attack.mitre.org/software/S0515)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
