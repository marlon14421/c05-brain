---
type: "Malware"
source: MITRE ATT&CK
id: "S1247"
source_url: "https://attack.mitre.org/software/S1247"
created: "2025-10-19"
modified: "2025-10-20"
---
# S1247: Embargo

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1247  
**Platforms:** ESXi, Linux, Windows  
**Tactics:** Not specified

## Source description

[Embargo](https://attack.mitre.org/software/S1247) is a ransomware variant written in Rust that has been active since at least May 2024.(Citation: Cyble Embargo Ransomware May 2024)(Citation: ESET Embargo Ransomware October 2024) [Embargo](https://attack.mitre.org/software/S1247) ransomware operations are associated with “double extortion” ransomware activity, where data is exfiltrated from victim environments prior to encryption, with threats to publish files if a ransom is not paid.(Citation: Cyble Embargo Ransomware May 2024)(Citation: ESET Embargo Ransomware October 2024) [Embargo](https://attack.mitre.org/software/S1247) ransomware has been known to be delivered through a loader known as MDeployer which also leverages a malware component known as MS4Killer that facilitates termination of processes operating on the victim hosts.(Citation: ESET Embargo Ransomware October 2024) [Embargo](https://attack.mitre.org/software/S1247) is also reportedly a Ransomware as a Service (RaaS).(Citation: ESET Embargo Ransomware October 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1247](https://attack.mitre.org/software/S1247)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
