---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2042"
source_url: "https://attack.mitre.org/detectionstrategies/DET0900#AN2042"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2042: Analytic 2042

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2042  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detects exploitation or abuse of SaaS security workflows resulting in disabled alerts, reduced retention, bypassed enforcement, role escalation, or tokenized persistence that weakens monitoring. Correlates unusual admin/API activity with visibility reduction.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2042](https://attack.mitre.org/detectionstrategies/DET0900#AN2042)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
