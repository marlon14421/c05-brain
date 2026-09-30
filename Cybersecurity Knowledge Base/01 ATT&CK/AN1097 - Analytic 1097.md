---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1097"
source_url: "https://attack.mitre.org/detectionstrategies/DET0391#AN1097"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1097: Analytic 1097

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1097  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for runtime data manipulations by detecting suspicious modification of application binaries, API hooking, or unexpected behavior from processes responsible for rendering or displaying data. Correlate registry edits, process creation, and unexpected binary hash mismatches.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1097](https://attack.mitre.org/detectionstrategies/DET0391#AN1097)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
