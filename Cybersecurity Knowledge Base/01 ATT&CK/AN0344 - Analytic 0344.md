---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0344"
source_url: "https://attack.mitre.org/detectionstrategies/DET0123#AN0344"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0344: Analytic 0344

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0344  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects mounting of external volumes followed by high-volume or sensitive file access via Finder, terminal, or third-party apps (e.g., rsync, zip).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0344](https://attack.mitre.org/detectionstrategies/DET0123#AN0344)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
