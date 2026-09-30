---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1162"
source_url: "https://attack.mitre.org/detectionstrategies/DET0413#AN1162"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1162: Analytic 1162

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1162  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Abuse of SaaS platforms such as Confluence, GitHub, SharePoint Online, or Slack to access excessive internal documentation or export source code/data. Includes use of tokens or browser automation from unapproved IPs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1162](https://attack.mitre.org/detectionstrategies/DET0413#AN1162)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
