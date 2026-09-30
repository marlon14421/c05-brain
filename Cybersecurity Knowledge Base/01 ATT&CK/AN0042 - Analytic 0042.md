---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0042"
source_url: "https://attack.mitre.org/detectionstrategies/DET0014#AN0042"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0042: Analytic 0042

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0042  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects files collected into user temp or shared directories followed by compression with ditto, zip, or custom scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0042](https://attack.mitre.org/detectionstrategies/DET0014#AN0042)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
