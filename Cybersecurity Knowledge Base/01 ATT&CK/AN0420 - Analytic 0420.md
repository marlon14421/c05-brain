---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0420"
source_url: "https://attack.mitre.org/detectionstrategies/DET0148#AN0420"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0420: Analytic 0420

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0420  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Forged SAML tokens may be used on Windows systems to authenticate to federated apps without normal Kerberos activity. Defenders may detect anomalous event correlation, where access to SaaS/O365 via SAML occurs without prior TGT requests or user logons.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0420](https://attack.mitre.org/detectionstrategies/DET0148#AN0420)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
