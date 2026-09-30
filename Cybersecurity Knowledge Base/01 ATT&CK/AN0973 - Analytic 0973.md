---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0973"
source_url: "https://attack.mitre.org/detectionstrategies/DET0344#AN0973"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0973: Analytic 0973

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0973  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects abuse of fileless storage mechanisms such as Registry keys, WMI classes, and Event Logs used to stage payloads, scripts, or encoded content outside traditional files.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0973](https://attack.mitre.org/detectionstrategies/DET0344#AN0973)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
