---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1538"
source_url: "https://attack.mitre.org/detectionstrategies/DET0559#AN1538"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1538: Analytic 1538

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1538  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlate process execution of shutdown/reboot commands (e.g., shutdown.exe, restart-computer) with host status change logs (Event IDs 1074, 6006) and absence of related administrative context (e.g., user not in Helpdesk group).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1538](https://attack.mitre.org/detectionstrategies/DET0559#AN1538)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
