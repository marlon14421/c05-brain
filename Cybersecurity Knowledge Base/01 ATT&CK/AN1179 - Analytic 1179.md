---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1179"
source_url: "https://attack.mitre.org/detectionstrategies/DET0419#AN1179"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1179: Analytic 1179

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1179  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Identify processes issuing repeated DNS queries to random-looking domains with abnormal entropy or word concatenations. Correlate resolver logs with high NXDOMAIN rates and auditd socket connections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1179](https://attack.mitre.org/detectionstrategies/DET0419#AN1179)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
