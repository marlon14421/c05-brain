---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1265"
source_url: "https://attack.mitre.org/detectionstrategies/DET0460#AN1265"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1265: Analytic 1265

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1265  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Same source IP performing multiple authentication attempts using known breached username/password combinations across different identities in Azure AD, Okta, or Duo

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1265](https://attack.mitre.org/detectionstrategies/DET0460#AN1265)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
