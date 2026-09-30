---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0283"
source_url: "https://attack.mitre.org/detectionstrategies/DET0102#AN0283"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0283: Analytic 0283

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0283  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects use of tools/scripts accessing input devices like /dev/input/* or evdev via suspicious processes lacking GUI context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0283](https://attack.mitre.org/detectionstrategies/DET0102#AN0283)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
