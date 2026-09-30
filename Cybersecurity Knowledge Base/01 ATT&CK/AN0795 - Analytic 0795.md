---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0795"
source_url: "https://attack.mitre.org/detectionstrategies/DET0286#AN0795"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0795: Analytic 0795

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0795  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Monitor SaaS mail platforms (Google Workspace, M365, Okta-integrated apps) for SendAs/SendOnBehalfOf operations where the delegated permissions are unusual or newly granted. Detect impersonation attempts where adversaries configure rules to auto-forward or auto-reply with impersonated content.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0795](https://attack.mitre.org/detectionstrategies/DET0286#AN0795)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
