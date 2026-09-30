---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1025"
source_url: "https://attack.mitre.org/detectionstrategies/DET0360#AN1025"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1025: Analytic 1025

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1025  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of domain group enumeration through command-line utilities such as 'net group /domain' or PowerShell cmdlets, followed by suspicious access to API calls or LSASS memory.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1025](https://attack.mitre.org/detectionstrategies/DET0360#AN1025)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
