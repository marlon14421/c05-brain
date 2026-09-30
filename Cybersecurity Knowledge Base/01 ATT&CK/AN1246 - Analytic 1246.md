---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1246"
source_url: "https://attack.mitre.org/detectionstrategies/DET0452#AN1246"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1246: Analytic 1246

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1246  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection correlates abnormal installation or modification of root or code-signing certificates, creation/modification of suspicious registry keys for trust providers, and unusual module loads from non-standard locations. Identifies unsigned or improperly signed executables bypassing trust prompts, combined with persistence artifacts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1246](https://attack.mitre.org/detectionstrategies/DET0452#AN1246)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
