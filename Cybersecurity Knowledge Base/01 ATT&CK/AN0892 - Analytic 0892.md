---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0892"
source_url: "https://attack.mitre.org/detectionstrategies/DET0317#AN0892"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0892: Analytic 0892

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0892  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Changes to security configurations such as disabling MFA requirements, reducing session token lifetimes, or turning off risk-based policies. Correlate admin logins with sudden policy downgrades.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0892](https://attack.mitre.org/detectionstrategies/DET0317#AN0892)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
