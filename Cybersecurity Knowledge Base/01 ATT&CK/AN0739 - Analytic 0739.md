---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0739"
source_url: "https://attack.mitre.org/detectionstrategies/DET0266#AN0739"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0739: Analytic 0739

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0739  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects removal of Apple Mail artifacts via AppleScript or direct deletion of mailbox content in ~/Library/Mail/, especially when preceded by Remote Login or C2-related API access.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0739](https://attack.mitre.org/detectionstrategies/DET0266#AN0739)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
