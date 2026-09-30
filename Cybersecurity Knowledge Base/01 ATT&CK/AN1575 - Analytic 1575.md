---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1575"
source_url: "https://attack.mitre.org/detectionstrategies/DET0571#AN1575"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1575: Analytic 1575

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1575  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects command-line or API-based creation/modification of Windows Services via `sc.exe`, `powershell.exe`, `services.exe`, or `ChangeServiceConfig`. Looks for creation/modification of autostart services via registry changes, file drops to `System32\services`, and anomalous parent-child process trees.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1575](https://attack.mitre.org/detectionstrategies/DET0571#AN1575)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
