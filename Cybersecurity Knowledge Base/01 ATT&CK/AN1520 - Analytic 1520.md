---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1520"
source_url: "https://attack.mitre.org/detectionstrategies/DET0550#AN1520"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1520: Analytic 1520

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1520  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Anomalous high-volume access to customer records in CRM software by a non-CRM admin user account, especially following initial authentication from a rare location or device. Behavior includes abnormal access to PII fields or data exports within a short time window.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1520](https://attack.mitre.org/detectionstrategies/DET0550#AN1520)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
