---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1365"
source_url: "https://attack.mitre.org/detectionstrategies/DET0495#AN1365"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1365: Analytic 1365

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1365  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Monitor email and document management systems for fraudulent invoices, impersonation of vendors, or BEC-style payment redirections. Detect abnormal editing of invoice templates, or emails containing known fraud language combined with attachment delivery.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1365](https://attack.mitre.org/detectionstrategies/DET0495#AN1365)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
