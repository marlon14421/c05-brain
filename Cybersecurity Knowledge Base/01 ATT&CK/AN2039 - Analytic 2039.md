---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2039"
source_url: "https://attack.mitre.org/detectionstrategies/DET0900#AN2039"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2039: Analytic 2039

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2039  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects exploitation attempts against security daemons or kernel security modules followed by daemon termination, disabled logging, module unload, audit stoppage, or reduced endpoint telemetry. Correlates local execution or network input with control degradation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2039](https://attack.mitre.org/detectionstrategies/DET0900#AN2039)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
