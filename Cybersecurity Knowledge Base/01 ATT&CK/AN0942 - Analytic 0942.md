---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0942"
source_url: "https://attack.mitre.org/detectionstrategies/DET0332#AN0942"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0942: Analytic 0942

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0942  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects execution of AutoHotKey or AutoIT interpreters or compiled scripts used for unauthorized automation, command execution, or payload delivery, correlated with anomalous process lineage, command-line arguments, or script creation events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0942](https://attack.mitre.org/detectionstrategies/DET0332#AN0942)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
