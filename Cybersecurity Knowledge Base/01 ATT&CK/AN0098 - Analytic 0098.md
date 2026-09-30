---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0098"
source_url: "https://attack.mitre.org/detectionstrategies/DET0034#AN0098"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0098: Analytic 0098

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0098  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects process enumeration using `esxcli system process list` or `ps` on ESXi shell or via unauthorized SSH sessions. Correlates with interactive sessions and abnormal user roles.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0098](https://attack.mitre.org/detectionstrategies/DET0034#AN0098)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
