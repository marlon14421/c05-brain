---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1193"
source_url: "https://attack.mitre.org/detectionstrategies/DET0426#AN1193"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1193: Analytic 1193

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1193  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes accessing raw logical drives (e.g., \.\C:) to bypass file system protections or directly manipulate data structures.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1193](https://attack.mitre.org/detectionstrategies/DET0426#AN1193)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
