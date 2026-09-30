---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1364"
source_url: "https://attack.mitre.org/detectionstrategies/DET0495#AN1364"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1364: Analytic 1364

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1364  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Monitor SaaS financial systems (e.g., QuickBooks, Workday, SAP S/4HANA cloud) for unauthorized access, rule changes, or mass export of financial data. Detect anomalous transfers initiated via SaaS APIs or new MFA-disabled logins targeting finance apps.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1364](https://attack.mitre.org/detectionstrategies/DET0495#AN1364)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
