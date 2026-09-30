---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1487"
source_url: "https://attack.mitre.org/detectionstrategies/DET0539#AN1487"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1487: Analytic 1487

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1487  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detects suspicious OAuth application integrations within Office 365 or Google Workspace environments, such as new app registrations, unexpected consent grants, or privilege assignments. Defenders should correlate between application creation/modification events and associated user or service principal activity to identify persistence via app integrations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1487](https://attack.mitre.org/detectionstrategies/DET0539#AN1487)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
