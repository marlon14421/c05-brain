---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2033"
source_url: "https://attack.mitre.org/detectionstrategies/DET0899#AN2033"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2033: Analytic 2033

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2033  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detects suspicious inbound communications or collaboration requests followed by rapid sensitive user actions such as file sharing changes, macro enablement, OAuth consent, credential submission, or financial workflow approvals that deviate from historical relationships or normal approval patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2033](https://attack.mitre.org/detectionstrategies/DET0899#AN2033)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
