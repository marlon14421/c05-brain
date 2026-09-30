---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0324"
source_url: "https://attack.mitre.org/detectionstrategies/DET0117#AN0324"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0324: Analytic 0324

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0324  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Creation or modification of Windows services or scheduled tasks with names or descriptions mimicking legitimate entries, followed by anomalous execution of untrusted binaries or LOLBAS.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0324](https://attack.mitre.org/detectionstrategies/DET0117#AN0324)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
