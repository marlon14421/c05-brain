---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0446"
source_url: "https://attack.mitre.org/detectionstrategies/DET0159#AN0446"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0446: Analytic 0446

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0446  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of USB-based remote access hardware (e.g., TinyPilot, PiKVM) attached to the host via drive or peripheral enumeration, triggering vendor identifiers or unusual EDID announcements.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0446](https://attack.mitre.org/detectionstrategies/DET0159#AN0446)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
