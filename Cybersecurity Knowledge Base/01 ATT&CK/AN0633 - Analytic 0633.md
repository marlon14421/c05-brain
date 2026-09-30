---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0633"
source_url: "https://attack.mitre.org/detectionstrategies/DET0227#AN0633"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0633: Analytic 0633

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0633  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes initiating outbound connections on uncommon ports or using protocols inconsistent with the assigned port. Correlating process creation with subsequent network connections reveals anomalies such as svchost.exe or Office applications using high, atypical ports.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0633](https://attack.mitre.org/detectionstrategies/DET0227#AN0633)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
