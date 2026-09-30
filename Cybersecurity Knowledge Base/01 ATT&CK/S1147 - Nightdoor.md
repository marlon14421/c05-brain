---
type: "Malware"
source: MITRE ATT&CK
id: "S1147"
source_url: "https://attack.mitre.org/software/S1147"
created: "2024-07-25"
modified: "2025-10-21"
---
# S1147: Nightdoor

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1147  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Nightdoor](https://attack.mitre.org/software/S1147) is a backdoor exclusively associated with [Daggerfly](https://attack.mitre.org/groups/G1034) operations. [Nightdoor](https://attack.mitre.org/software/S1147) uses common libraries with [MgBot](https://attack.mitre.org/software/S1146) and [MacMa](https://attack.mitre.org/software/S1016), linking these malware families together.(Citation: ESET EvasivePanda 2024)(Citation: Symantec Daggerfly 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1147](https://attack.mitre.org/software/S1147)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
