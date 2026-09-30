---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0362"
source_url: "https://attack.mitre.org/detectionstrategies/DET0128#AN0362"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0362: Analytic 0362

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0362  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Modification of plist files to set apple.awt.UIElement or similar flags hiding app icons and windows, and dscl/command-line activity that suppresses visibility. Defender view: correlation of plist modifications with unexpected hidden user applications.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0362](https://attack.mitre.org/detectionstrategies/DET0128#AN0362)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
