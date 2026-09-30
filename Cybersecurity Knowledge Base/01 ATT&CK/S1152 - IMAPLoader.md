---
type: "Malware"
source: MITRE ATT&CK
id: "S1152"
source_url: "https://attack.mitre.org/software/S1152"
created: "2024-08-14"
modified: "2024-10-02"
---
# S1152: IMAPLoader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1152  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[IMAPLoader](https://attack.mitre.org/software/S1152) is a .NET-based loader malware exclusively associated with [CURIUM](https://attack.mitre.org/groups/G1012) operations since at least 2022. [IMAPLoader](https://attack.mitre.org/software/S1152) leverages email protocols for command and control and payload delivery.(Citation: PWC Yellow Liderc 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1152](https://attack.mitre.org/software/S1152)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
