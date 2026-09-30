---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0418"
source_url: "https://attack.mitre.org/detectionstrategies/DET0148#AN0418"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0418: Analytic 0418

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0418  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Forged SAML tokens can be observed as authentication attempts with valid signatures but missing expected preceding Kerberos or authentication events. Defenders may correlate SAML assertions with absent Event IDs 4769, 1200, or 1202, or tokens issued with abnormal lifetimes, issuers, or claims compared to baseline.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0418](https://attack.mitre.org/detectionstrategies/DET0148#AN0418)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
