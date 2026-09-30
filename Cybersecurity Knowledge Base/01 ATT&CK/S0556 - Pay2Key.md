---
type: "Malware"
source: MITRE ATT&CK
id: "S0556"
source_url: "https://attack.mitre.org/software/S0556"
created: "2021-01-04"
modified: "2025-04-25"
---
# S0556: Pay2Key

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0556  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Pay2Key](https://attack.mitre.org/software/S0556) is a ransomware written in C++ that has been used by [Fox Kitten](https://attack.mitre.org/groups/G0117) since at least July 2020 including campaigns against Israeli companies. [Pay2Key](https://attack.mitre.org/software/S0556) has been incorporated with a leak site to display stolen sensitive information to further pressure victims into payment.(Citation: ClearkSky Fox Kitten February 2020)(Citation: Check Point Pay2Key November 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0556](https://attack.mitre.org/software/S0556)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
