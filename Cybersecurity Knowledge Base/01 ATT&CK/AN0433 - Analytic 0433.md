---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0433"
source_url: "https://attack.mitre.org/detectionstrategies/DET0151#AN0433"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0433: Analytic 0433

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0433  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Interactive or remote shell/API invocation of esxcli system clock get or querying time parameters via hostd/vpxa shortly followed by time/ntp configuration checks or scheduled task creation, executed by non-standard accounts or outside maintenance windows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0433](https://attack.mitre.org/detectionstrategies/DET0151#AN0433)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
