---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2038"
source_url: "https://attack.mitre.org/detectionstrategies/DET0900#AN2038"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2038: Analytic 2038

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2038  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious interactions with security products followed by service crashes, unexpected restarts, driver unloads, telemetry gaps, or tamper-state changes. Correlates exploit precursor behavior with immediate degradation of defensive services and follow-on process execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2038](https://attack.mitre.org/detectionstrategies/DET0900#AN2038)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
