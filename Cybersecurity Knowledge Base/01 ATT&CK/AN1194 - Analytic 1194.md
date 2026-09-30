---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1194"
source_url: "https://attack.mitre.org/detectionstrategies/DET0426#AN1194"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1194: Analytic 1194

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1194  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

CLI or automated utilities accessing raw device volumes or flash storage directly (e.g., via `copy flash:`, `format`, or `partition` commands).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1194](https://attack.mitre.org/detectionstrategies/DET0426#AN1194)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
