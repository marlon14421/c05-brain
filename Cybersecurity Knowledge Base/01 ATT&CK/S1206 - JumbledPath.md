---
type: "Malware"
source: MITRE ATT&CK
id: "S1206"
source_url: "https://attack.mitre.org/software/S1206"
created: "2025-02-25"
modified: "2025-04-15"
---
# S1206: JumbledPath

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1206  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[JumbledPath](https://attack.mitre.org/software/S1206) is a custom-built utility written in GO that has been used by [Salt Typhoon](https://attack.mitre.org/groups/G1045) since at least 2024 for packet capture on remote Cisco devices. [JumbledPath](https://attack.mitre.org/software/S1206) is compiled as an ELF binary using x86-64 architecture which makes it potentially useable across Linux operating systems and network devices from multiple vendors.(Citation: Cisco Salt Typhoon FEB 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1206](https://attack.mitre.org/software/S1206)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
