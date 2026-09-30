---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0614"
source_url: "https://attack.mitre.org/detectionstrategies/DET0219#AN0614"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0614: Analytic 0614

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0614  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of Windows container escape attempts by observing processes accessing host directories, symbolic link abuse, or privilege escalation attempts. Defenders may detect anomalous process execution with access to system-level directories outside of container boundaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0614](https://attack.mitre.org/detectionstrategies/DET0219#AN0614)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
