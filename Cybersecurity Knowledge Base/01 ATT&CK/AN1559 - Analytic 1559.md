---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1559"
source_url: "https://attack.mitre.org/detectionstrategies/DET0563#AN1559"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1559: Analytic 1559

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1559  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detection of CLI commands that disable history logging such as 'no logging'. Anomalous lack of new commands in session logs while activity persists is a strong signal.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1559](https://attack.mitre.org/detectionstrategies/DET0563#AN1559)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
