---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1472"
source_url: "https://attack.mitre.org/detectionstrategies/DET0532#AN1472"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1472: Analytic 1472

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1472  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects behavioral sequence where an adversary gains elevated privileges and clears event logs using native binaries (e.g., wevtutil), PowerShell, or direct file deletion of .evtx files.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1472](https://attack.mitre.org/detectionstrategies/DET0532#AN1472)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
