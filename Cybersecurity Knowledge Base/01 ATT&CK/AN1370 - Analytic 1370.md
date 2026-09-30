---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1370"
source_url: "https://attack.mitre.org/detectionstrategies/DET0497#AN1370"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1370: Analytic 1370

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1370  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects kill/systemctl/service commands against EDR, auditd, falco, osquery, rsyslog, journald, or agent processes; configuration edits disabling startup; module unload attempts; abrupt cessation of logs after privileged shell execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1370](https://attack.mitre.org/detectionstrategies/DET0497#AN1370)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
