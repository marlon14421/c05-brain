---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0650"
source_url: "https://attack.mitre.org/detectionstrategies/DET0234#AN0650"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0650: Analytic 0650

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0650  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Unsigned processes accessing system memory or launching known credential scraping tools (e.g., osascript, dylib injections) to access the Keychain or sensitive memory regions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0650](https://attack.mitre.org/detectionstrategies/DET0234#AN0650)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
