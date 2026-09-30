---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0333"
source_url: "https://attack.mitre.org/detectionstrategies/DET0119#AN0333"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0333: Analytic 0333

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0333  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects manipulation of PNG, JPG, or GIF files by user-initiated scripts followed by script execution or exfiltration behavior, especially from `osascript`, `python`, or `bash`, in combination with LaunchAgent persistence or curl activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0333](https://attack.mitre.org/detectionstrategies/DET0119#AN0333)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
