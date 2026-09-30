---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0680"
source_url: "https://attack.mitre.org/detectionstrategies/DET0242#AN0680"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0680: Analytic 0680

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0680  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Unusual or excessive database/table exports from SaaS database platforms (e.g., Snowflake, Firebase, BigQuery, Airtable) by users or apps not in known analytics or dev groups. Defender observes access patterns outside baseline working hours or with new query templates, and correlates those with audit logs or file downloads.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0680](https://attack.mitre.org/detectionstrategies/DET0242#AN0680)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
