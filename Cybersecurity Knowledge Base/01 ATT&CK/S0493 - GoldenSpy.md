---
type: "Malware"
source: MITRE ATT&CK
id: "S0493"
source_url: "https://attack.mitre.org/software/S0493"
created: "2020-07-23"
modified: "2024-04-11"
---
# S0493: GoldenSpy

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0493  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[GoldenSpy](https://attack.mitre.org/software/S0493) is a backdoor malware which has been packaged with legitimate tax preparation software. [GoldenSpy](https://attack.mitre.org/software/S0493) was discovered targeting organizations in China, being delivered with the "Intelligent Tax" software suite which is produced by the Golden Tax Department of Aisino Credit Information Co. and required to pay local taxes.(Citation: Trustwave GoldenSpy June 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0493](https://attack.mitre.org/software/S0493)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
