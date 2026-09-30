---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0555"
source_url: "https://attack.mitre.org/detectionstrategies/DET0193#AN0555"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0555: Analytic 0555

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0555  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Identify unauthorized creation, deletion, or modification of business-critical stored data such as Office documents, database files, and log archives. Detect anomalous processes modifying stored data outside of expected workflows (e.g., non-database processes modifying database files).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0555](https://attack.mitre.org/detectionstrategies/DET0193#AN0555)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
