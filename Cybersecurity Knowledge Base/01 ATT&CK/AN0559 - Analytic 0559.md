---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0559"
source_url: "https://attack.mitre.org/detectionstrategies/DET0195#AN0559"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0559: Analytic 0559

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0559  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of built-in tools (e.g., ipconfig, route, netsh) or PowerShell/WMI queries to enumerate IP, MAC, interface status, or routing configuration.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0559](https://attack.mitre.org/detectionstrategies/DET0195#AN0559)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
