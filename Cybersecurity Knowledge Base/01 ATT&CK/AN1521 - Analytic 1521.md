---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1521"
source_url: "https://attack.mitre.org/detectionstrategies/DET0551#AN1521"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1521: Analytic 1521

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1521  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Series of authentication failures (Event ID 4625) targeting the same or similar user accounts over time from one or more remote IPs

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1521](https://attack.mitre.org/detectionstrategies/DET0551#AN1521)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
