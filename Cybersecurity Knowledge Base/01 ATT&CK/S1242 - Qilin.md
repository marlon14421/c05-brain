---
type: "Malware"
source: MITRE ATT&CK
id: "S1242"
source_url: "https://attack.mitre.org/software/S1242"
created: "2025-09-26"
modified: "2026-04-23"
---
# S1242: Qilin

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1242  
**Platforms:** ESXi, Windows, Linux  
**Tactics:** Not specified

## Source description

[Qilin](https://attack.mitre.org/software/S1242) is a ransomware family operated as a ransomware-as-a-service (RaaS) that has been active since at least 2022. It includes variants written in Go and Rust capable of targeting Windows, Linux, and VMware ESXi environments. [Qilin](https://attack.mitre.org/software/S1242) shares functionality overlaps with [Black Basta](https://attack.mitre.org/software/S1070), [REvil](https://attack.mitre.org/software/S0496), and [BlackCat](https://attack.mitre.org/software/S1068) ransomware. [Qilin](https://attack.mitre.org/software/S1242) affiliates have targeted multiple entities worldwide with the majority of victims in the US, France, Canada, and the UK, primarily in the manufacturing, technology, financial services, and healthcare sectors.(Citation: Trend Micro Agenda Ransomware AUG 2022)(Citation: SentinelOne Qilin NOV 2022)(Citation: BushidoToken Qilin RaaS JUN 2024)(Citation: Sophos Qilin MSP APR 2025)(Citation: Trend Micro Agenda Ransomware OCT 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1242](https://attack.mitre.org/software/S1242)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
