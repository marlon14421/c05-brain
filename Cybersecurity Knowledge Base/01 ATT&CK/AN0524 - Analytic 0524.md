---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0524"
source_url: "https://attack.mitre.org/detectionstrategies/DET0184#AN0524"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0524: Analytic 0524

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0524  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Tracks suspicious use of ESXi shell commands or PowerCLI to delete logs, rotate system files, or tamper with hostd/vpxa history.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0524](https://attack.mitre.org/detectionstrategies/DET0184#AN0524)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
