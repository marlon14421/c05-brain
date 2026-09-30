---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0208"
source_url: "https://attack.mitre.org/detectionstrategies/DET0075#AN0208"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0208: Analytic 0208

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0208  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Configuration of internal NAT or proxy rules that redirect traffic between client segments internally (e.g., site-to-site port forwarding). Often used to relay internal beaconing or move traffic laterally through trust zones.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0208](https://attack.mitre.org/detectionstrategies/DET0075#AN0208)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
