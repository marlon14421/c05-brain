---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0421"
source_url: "https://attack.mitre.org/detectionstrategies/DET0148#AN0421"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0421: Analytic 0421

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0421  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Forged SAML tokens can appear as SaaS logins where authentication succeeded without MFA, or where tokens contain claims inconsistent with the user profile. Look for concurrent sessions across different geographies with the same SAML assertion ID.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0421](https://attack.mitre.org/detectionstrategies/DET0148#AN0421)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
