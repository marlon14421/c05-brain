---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0153"
source_url: "https://attack.mitre.org/detectionstrategies/DET0056#AN0153"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0153: Analytic 0153

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0153  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of unauthorized modifications to Windows root certificate stores by monitoring registry keys, certificate installation processes, and creation of new certificate entries not in baseline trusted lists.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0153](https://attack.mitre.org/detectionstrategies/DET0056#AN0153)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
