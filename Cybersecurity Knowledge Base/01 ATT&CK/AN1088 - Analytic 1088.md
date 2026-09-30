---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1088"
source_url: "https://attack.mitre.org/detectionstrategies/DET0386#AN1088"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1088: Analytic 1088

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1088  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Use of AWS CLI (`aws iam list-users`, `list-roles`), Azure CLI (`az ad user list`), or GCP CLI (`gcloud iam service-accounts list`) from endpoints or cloud shells where such activity is unexpected.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1088](https://attack.mitre.org/detectionstrategies/DET0386#AN1088)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
