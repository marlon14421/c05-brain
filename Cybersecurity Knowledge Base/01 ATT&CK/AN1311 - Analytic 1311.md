---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1311"
source_url: "https://attack.mitre.org/detectionstrategies/DET0476#AN1311"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1311: Analytic 1311

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1311  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Monitors Mail.app database or maildir file access, automation via AppleScript, and abnormal mail rule creation using scripting or UI automation frameworks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1311](https://attack.mitre.org/detectionstrategies/DET0476#AN1311)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
