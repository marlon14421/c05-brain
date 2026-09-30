---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1221"
source_url: "https://attack.mitre.org/detectionstrategies/DET0441#AN1221"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1221: Analytic 1221

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1221  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects the creation, modification, or deletion of scheduled tasks through Task Scheduler, WMI, PowerShell, or API-based methods followed by execution from svchost.exe or taskeng.exe. Includes detection of hidden or anomalous scheduled tasks, especially those created under SYSTEM or suspicious user contexts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1221](https://attack.mitre.org/detectionstrategies/DET0441#AN1221)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
