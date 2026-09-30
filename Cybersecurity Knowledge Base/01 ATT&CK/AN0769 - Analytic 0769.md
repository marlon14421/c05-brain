---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0769"
source_url: "https://attack.mitre.org/detectionstrategies/DET0275#AN0769"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0769: Analytic 0769

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0769  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

The adversary invokes built-in scripting or decoding tools like base64, plutil, or AppleScript-based utilities to decode files embedded in staging artifacts. Decoding often occurs post-download or as part of post-exploitation payload deployment via zsh, python, or osascript.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0769](https://attack.mitre.org/detectionstrategies/DET0275#AN0769)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
