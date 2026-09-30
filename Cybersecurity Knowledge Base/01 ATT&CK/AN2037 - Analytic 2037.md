---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2037"
source_url: "https://attack.mitre.org/detectionstrategies/DET0899#AN2037"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2037: Analytic 2037

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2037  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects users executing commands copied from chats, tickets, or emails, including curl|bash patterns, shell script launches from temp directories, credential changes, or SSH key additions shortly after communication events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2037](https://attack.mitre.org/detectionstrategies/DET0899#AN2037)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
