---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0718"
source_url: "https://attack.mitre.org/detectionstrategies/DET0260#AN0718"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0718: Analytic 0718

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0718  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Forged web credentials may manifest as anomalous SAML token issuance, OpenID Connect token minting, or Zimbra pre-auth key usage. Defenders may see tokens issued without normal authentication events, multiple valid tokens generated simultaneously, or signing anomalies in IdP logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0718](https://attack.mitre.org/detectionstrategies/DET0260#AN0718)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
