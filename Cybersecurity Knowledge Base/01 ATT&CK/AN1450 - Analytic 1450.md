---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1450"
source_url: "https://attack.mitre.org/detectionstrategies/DET0524#AN1450"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1450: Analytic 1450

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1450  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Remote knock sequence followed by PF/socketfilterfw rule update or a background process listening on a new port; then a successful TCP session. Also flags WoL magic packets on local segment.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1450](https://attack.mitre.org/detectionstrategies/DET0524#AN1450)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
