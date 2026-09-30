---
type: "Malware"
source: MITRE ATT&CK
id: "S1032"
source_url: "https://attack.mitre.org/software/S1032"
created: "2022-08-11"
modified: "2024-04-11"
---
# S1032: PyDCrypt

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1032  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[PyDCrypt](https://attack.mitre.org/software/S1032) is malware written in Python designed to deliver [DCSrv](https://attack.mitre.org/software/S1033). It has been used by [Moses Staff](https://attack.mitre.org/groups/G1009) since at least September 2021, with each sample tailored for its intended victim organization.(Citation: Checkpoint MosesStaff Nov 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1032](https://attack.mitre.org/software/S1032)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
