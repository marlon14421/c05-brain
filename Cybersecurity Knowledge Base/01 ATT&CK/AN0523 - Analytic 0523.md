---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0523"
source_url: "https://attack.mitre.org/detectionstrategies/DET0184#AN0523"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0523: Analytic 0523

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0523  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Monitors tampering with audit logs, volumes, or mounted storage often used for side-channel logging (e.g., /var/log inside containers) post-compromise.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0523](https://attack.mitre.org/detectionstrategies/DET0184#AN0523)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
