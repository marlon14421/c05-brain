---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1402"
source_url: "https://attack.mitre.org/detectionstrategies/DET0509#AN1402"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1402: Analytic 1402

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1402  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious access to browser session cookie storage (e.g., Chrome’s `Cookies` SQLite DB) or memory reads of browser processes. Anomalous injection or memory dump utilities targeting browser processes such as `chrome.exe`, `firefox.exe`, or `msedge.exe`.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1402](https://attack.mitre.org/detectionstrategies/DET0509#AN1402)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
