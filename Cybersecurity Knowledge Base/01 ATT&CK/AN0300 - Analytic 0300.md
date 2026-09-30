---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0300"
source_url: "https://attack.mitre.org/detectionstrategies/DET0107#AN0300"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0300: Analytic 0300

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0300  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Correlation of Mail.app logs with Safari/Chrome activity. Suspicious behavior includes email links → Safari/Chrome accessing newly registered or lookalike domains → osascript or Terminal spawned unexpectedly.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0300](https://attack.mitre.org/detectionstrategies/DET0107#AN0300)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
