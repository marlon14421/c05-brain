---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0148"
source_url: "https://attack.mitre.org/detectionstrategies/DET0054#AN0148"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0148: Analytic 0148

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0148  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Delivery of suspicious internal communication (e.g., Thunderbird, Evolution) using compromised internal accounts. Sequence of: unexpected user activity + mail transfer logs + download or execution of attachments.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0148](https://attack.mitre.org/detectionstrategies/DET0054#AN0148)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
