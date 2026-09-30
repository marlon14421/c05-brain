---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1563"
source_url: "https://attack.mitre.org/detectionstrategies/DET0565#AN1563"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1563: Analytic 1563

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1563  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Execution of commands to query system locale and language settings, such as 'defaults read -g AppleLocale' or 'systemsetup -gettimezone'. Unusual parent processes or execution contexts of these commands may indicate adversarial discovery.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1563](https://attack.mitre.org/detectionstrategies/DET0565#AN1563)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
