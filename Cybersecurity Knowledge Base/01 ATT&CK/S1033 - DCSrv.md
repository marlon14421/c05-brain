---
type: "Malware"
source: MITRE ATT&CK
id: "S1033"
source_url: "https://attack.mitre.org/software/S1033"
created: "2022-08-11"
modified: "2024-04-11"
---
# S1033: DCSrv

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1033  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DCSrv](https://attack.mitre.org/software/S1033) is destructive malware that has been used by [Moses Staff](https://attack.mitre.org/groups/G1009) since at least September 2021. Though [DCSrv](https://attack.mitre.org/software/S1033) has ransomware-like capabilities, [Moses Staff](https://attack.mitre.org/groups/G1009) does not demand ransom or offer a decryption key.(Citation: Checkpoint MosesStaff Nov 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1033](https://attack.mitre.org/software/S1033)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
