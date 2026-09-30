---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0334"
source_url: "https://attack.mitre.org/detectionstrategies/DET0120#AN0334"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0334: Analytic 0334

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0334  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlated user account modification (reset, disable, deletion) events with anomalous process lineage (e.g., PowerShell or net.exe from an interactive session), especially outside of IT admin change windows or by non-admin users.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0334](https://attack.mitre.org/detectionstrategies/DET0120#AN0334)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
