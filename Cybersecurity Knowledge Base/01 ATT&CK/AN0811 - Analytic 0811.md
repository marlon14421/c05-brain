---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0811"
source_url: "https://attack.mitre.org/detectionstrategies/DET0291#AN0811"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0811: Analytic 0811

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0811  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detects SaaS web login followed by dashboard or web GUI page views from unfamiliar locations, devices, or access patterns. Identifies use of sensitive reporting or configuration consoles accessed from high-risk accounts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0811](https://attack.mitre.org/detectionstrategies/DET0291#AN0811)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
