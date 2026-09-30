---
type: "Malware"
source: MITRE ATT&CK
id: "S0448"
source_url: "https://attack.mitre.org/software/S0448"
created: "2020-05-14"
modified: "2024-04-11"
---
# S0448: Rising Sun

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0448  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Rising Sun](https://attack.mitre.org/software/S0448) is a modular backdoor that was used extensively in [Operation Sharpshooter](https://attack.mitre.org/campaigns/C0013) between 2017 and 2019. [Rising Sun](https://attack.mitre.org/software/S0448) infected at least 87 organizations around the world, including nuclear, defense, energy, and financial service companies. Security researchers assessed [Rising Sun](https://attack.mitre.org/software/S0448) included some source code from [Lazarus Group](https://attack.mitre.org/groups/G0032)'s Trojan Duuzer.(Citation: McAfee Sharpshooter December 2018)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0448](https://attack.mitre.org/software/S0448)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
