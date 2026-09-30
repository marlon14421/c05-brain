---
type: "Malware"
source: MITRE ATT&CK
id: "S1078"
source_url: "https://attack.mitre.org/software/S1078"
created: "2023-06-14"
modified: "2023-10-12"
---
# S1078: RotaJakiro

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1078  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[RotaJakiro](https://attack.mitre.org/software/S1078) is a 64-bit Linux backdoor used by [APT32](https://attack.mitre.org/groups/G0050). First seen in 2018, it uses a plugin architecture to extend capabilities. [RotaJakiro](https://attack.mitre.org/software/S1078) can determine it's permission level and execute according to access type (`root` or `user`).(Citation: RotaJakiro 2021 netlab360 analysis)(Citation: netlab360 rotajakiro vs oceanlotus)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1078](https://attack.mitre.org/software/S1078)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
