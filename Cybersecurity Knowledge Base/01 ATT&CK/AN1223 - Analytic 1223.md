---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1223"
source_url: "https://attack.mitre.org/detectionstrategies/DET0443#AN1223"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1223: Analytic 1223

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1223  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects anomalous process execution patterns where a process's parent terminates quickly after process creation or is re-parented to 'init' (PID 1), often indicating double-fork or daemon-style detachment. These behaviors sever the parent-child relationship and obscure the execution origin in process tree analysis.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1223](https://attack.mitre.org/detectionstrategies/DET0443#AN1223)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
