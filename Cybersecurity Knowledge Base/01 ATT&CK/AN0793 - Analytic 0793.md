---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0793"
source_url: "https://attack.mitre.org/detectionstrategies/DET0286#AN0793"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0793: Analytic 0793

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0793  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Monitor mail server logs (Postfix, Sendmail, Exim) for anomalous From headers mismatching authenticated SMTP identities. Detect abnormal relay attempts, spoofed envelope-from values, or large-scale outbound campaigns targeting internal users.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0793](https://attack.mitre.org/detectionstrategies/DET0286#AN0793)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
