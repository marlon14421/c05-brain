---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0284"
source_url: "https://attack.mitre.org/detectionstrategies/DET0102#AN0284"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0284: Analytic 0284

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0284  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Monitors for TCC-bypassing or unauthorized access to input services like IOHIDSystem or Quartz Event Services used in keylogging or screen monitoring.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0284](https://attack.mitre.org/detectionstrategies/DET0102#AN0284)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
