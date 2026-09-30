---
type: "Malware"
source: MITRE ATT&CK
id: "S1146"
source_url: "https://attack.mitre.org/software/S1146"
created: "2024-07-25"
modified: "2024-10-10"
---
# S1146: MgBot

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1146  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[MgBot](https://attack.mitre.org/software/S1146) is a modular malware framework exclusively associated with [Daggerfly](https://attack.mitre.org/groups/G1034) operations since at least 2012. [MgBot](https://attack.mitre.org/software/S1146) was developed in C++ and features a module design with multiple available plugins that have been under active development through 2024.(Citation: Szappanos MgBot 2014)(Citation: ESET EvasivePanda 2023)(Citation: Symantec Daggerfly 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1146](https://attack.mitre.org/software/S1146)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
