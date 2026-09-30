---
type: "Malware"
source: MITRE ATT&CK
id: "S1199"
source_url: "https://attack.mitre.org/software/S1199"
created: "2025-01-24"
modified: "2025-10-21"
---
# S1199: LockBit 2.0

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1199  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LockBit 2.0](https://attack.mitre.org/software/S1199) is an affiliate-based Ransomware-as-a-Service (RaaS) that has been in use since at least June 2021 as the successor to LockBit Ransomware. [LockBit 2.0](https://attack.mitre.org/software/S1199) has versions capable of infecting Windows and VMware ESXi virtual machines, and has been observed targeting multiple industry verticals globally.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Palo Alto Lockbit 2.0 JUN 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1199](https://attack.mitre.org/software/S1199)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
