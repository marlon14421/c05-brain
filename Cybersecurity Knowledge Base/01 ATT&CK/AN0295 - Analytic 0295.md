---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0295"
source_url: "https://attack.mitre.org/detectionstrategies/DET0105#AN0295"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0295: Analytic 0295

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0295  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Sudden valid logins from accounts that previously had credentials dumped but had not authenticated successfully in the past; correlated with timeline of suspected hash cracking

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0295](https://attack.mitre.org/detectionstrategies/DET0105#AN0295)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
