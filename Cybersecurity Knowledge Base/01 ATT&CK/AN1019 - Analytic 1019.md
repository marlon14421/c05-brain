---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1019"
source_url: "https://attack.mitre.org/detectionstrategies/DET0358#AN1019"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1019: Analytic 1019

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1019  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detection of excessive or programmatic access to Confluence spaces or pages, particularly by privileged users, through a combination of access logs, API usage, and identity context. Correlates logon sessions, user roles, and abnormal document viewing or export behavior. Identifies burst access patterns and tools/scripts abusing the Confluence API for mass enumeration or data scraping.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1019](https://attack.mitre.org/detectionstrategies/DET0358#AN1019)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
