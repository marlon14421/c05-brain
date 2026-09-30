---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0176"
source_url: "https://attack.mitre.org/detectionstrategies/DET0064#AN0176"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0176: Analytic 0176

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0176  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unquoted service or shortcut paths that contain spaces and allow path interception by higher-level executables. Defender observes registry service configurations with unquoted paths, file creation of executables in parent directories of unquoted paths, and subsequent process execution from unexpected locations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0176](https://attack.mitre.org/detectionstrategies/DET0064#AN0176)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
