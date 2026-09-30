---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0458"
source_url: "https://attack.mitre.org/detectionstrategies/DET0161#AN0458"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0458: Analytic 0458

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0458  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Chain: (1) cloud API calls that fetch tenant/organization password policy (e.g., AWS `GetAccountPasswordPolicy`, GCP/OCI equivalents or IAM settings reads); (2) within a short window, the same principal creates users, rotates creds, or changes auth settings. Use cloud audit logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0458](https://attack.mitre.org/detectionstrategies/DET0161#AN0458)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
