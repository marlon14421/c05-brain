---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0695"
source_url: "https://attack.mitre.org/detectionstrategies/DET0251#AN0695"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0695: Analytic 0695

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0695  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects adversarial use of cloud-native APIs (e.g., AWS IAM, Azure RBAC, GCP Identity) to enumerate cloud group memberships or policy mappings via unauthorized sessions or scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0695](https://attack.mitre.org/detectionstrategies/DET0251#AN0695)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
