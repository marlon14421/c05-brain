---
type: "Malware"
source: MITRE ATT&CK
id: "S1202"
source_url: "https://attack.mitre.org/software/S1202"
created: "2025-02-05"
modified: "2025-10-21"
---
# S1202: LockBit 3.0

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1202  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LockBit 3.0](https://attack.mitre.org/software/S1202) is an evolution of the LockBit Ransomware-as-a-Service (RaaS) offering with similarities to BlackMatter and [BlackCat](https://attack.mitre.org/software/S1068) ransomware. [LockBit 3.0](https://attack.mitre.org/software/S1202) has been in use since at least June 2022 and features enhanced defense evasion and exfiltration tactics, robust encryption methods for Windows and VMware ESXi systems, and a more refined RaaS structure over its predecessors such as [LockBit 2.0](https://attack.mitre.org/software/S1199).(Citation: Sentinel Labs LockBit 3.0 JUL 2022)(Citation: Joint Cybersecurity Advisory LockBit JUN 2023)(Citation: Joint Cybersecurity Advisory LockBit 3.0 MAR 2023)(Citation: INCIBE-CERT LockBit MAR 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1202](https://attack.mitre.org/software/S1202)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
