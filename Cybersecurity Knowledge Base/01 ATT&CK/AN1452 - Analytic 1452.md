---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1452"
source_url: "https://attack.mitre.org/detectionstrategies/DET0525#AN1452"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1452: Analytic 1452

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1452  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of processes executing system environment inspection operations followed by access to OS configuration APIs or registry locations that expose OS version, architecture, patch level, or hardware characteristics. Defenders observe process execution retrieving system configuration metadata immediately after process startup.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1452](https://attack.mitre.org/detectionstrategies/DET0525#AN1452)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
