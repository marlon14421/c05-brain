---
type: "Malware"
source: MITRE ATT&CK
id: "S1051"
source_url: "https://attack.mitre.org/software/S1051"
created: "2022-12-12"
modified: "2024-04-11"
---
# S1051: KEYPLUG

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1051  
**Platforms:** Linux, Windows  
**Tactics:** Not specified

## Source description

[KEYPLUG](https://attack.mitre.org/software/S1051) is a modular backdoor written in C++, with Windows and Linux variants, that has been used by [APT41](https://attack.mitre.org/groups/G0096) since at least June 2021.(Citation: Mandiant APT41)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1051](https://attack.mitre.org/software/S1051)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
