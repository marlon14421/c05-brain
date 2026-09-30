---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1533"
source_url: "https://attack.mitre.org/detectionstrategies/DET0554#AN1533"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1533: Analytic 1533

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1533  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Observation of `blueutil`/`networksetup` commands or low-level APIs toggling Bluetooth or initiating transfers, especially if paired with recent large file read activity by non-GUI processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1533](https://attack.mitre.org/detectionstrategies/DET0554#AN1533)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
