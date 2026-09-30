---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2034"
source_url: "https://attack.mitre.org/detectionstrategies/DET0899#AN2034"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2034: Analytic 2034

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2034  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detects consent grants, password resets, role changes, external sharing, or token creation shortly after user interaction with messages, invites, or help desk workflows. Emphasis is placed on unusual requester relationships, new device context, or off-hours approvals.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2034](https://attack.mitre.org/detectionstrategies/DET0899#AN2034)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
