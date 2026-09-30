---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0310"
source_url: "https://attack.mitre.org/detectionstrategies/DET0111#AN0310"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0310: Analytic 0310

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0310  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detection monitors SaaS collaboration tools (e.g., Slack, Zoom, Jira) for messages or files containing credential-like patterns, or for suspicious API calls retrieving bulk chat histories by non-admin users. Identifies adversary behavior chains where chat logs are queried via APIs or integration bots to systematically extract sensitive material.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0310](https://attack.mitre.org/detectionstrategies/DET0111#AN0310)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
