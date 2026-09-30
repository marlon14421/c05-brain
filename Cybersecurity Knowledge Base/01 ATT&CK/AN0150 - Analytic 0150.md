---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0150"
source_url: "https://attack.mitre.org/detectionstrategies/DET0054#AN0150"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0150: Analytic 0150

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0150  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Internal spearphishing via SaaS applications (e.g., Slack, Teams, Gmail): message sent from compromised user with attachment or URL, followed by click and credential access behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0150](https://attack.mitre.org/detectionstrategies/DET0054#AN0150)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
