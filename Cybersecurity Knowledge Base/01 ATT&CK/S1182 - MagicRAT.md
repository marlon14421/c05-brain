---
type: "Malware"
source: MITRE ATT&CK
id: "S1182"
source_url: "https://attack.mitre.org/software/S1182"
created: "2024-12-30"
modified: "2025-04-10"
---
# S1182: MagicRAT

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1182  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[MagicRAT](https://attack.mitre.org/software/S1182) is a remote access tool developed in C++ and exclusively used by the [Lazarus Group](https://attack.mitre.org/groups/G0032) threat actor in operations. [MagicRAT](https://attack.mitre.org/software/S1182) allows for arbitrary command execution on victim machines and provides basic remote access functionality.(Citation: Cisco MagicRAT 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1182](https://attack.mitre.org/software/S1182)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
