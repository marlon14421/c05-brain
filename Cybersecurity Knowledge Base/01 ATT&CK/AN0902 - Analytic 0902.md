---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0902"
source_url: "https://attack.mitre.org/detectionstrategies/DET0319#AN0902"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0902: Analytic 0902

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0902  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Adversaries leverage M365 or Google Workspace APIs to create users, service accounts, or guest accounts. Follow-on behaviors include login activity, role escalation, or service principal token generation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0902](https://attack.mitre.org/detectionstrategies/DET0319#AN0902)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
