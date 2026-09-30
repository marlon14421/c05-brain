---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1003"
source_url: "https://attack.mitre.org/detectionstrategies/DET0353#AN1003"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1003: Analytic 1003

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1003  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

User creation or modification via dscl with IsHidden=1, UID<500, or plist edits to com.apple.loginwindow Hide500Users flag. Defender view: correlation of hidden account attributes with login screen exclusion.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1003](https://attack.mitre.org/detectionstrategies/DET0353#AN1003)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
