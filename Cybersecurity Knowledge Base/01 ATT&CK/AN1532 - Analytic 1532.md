---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1532"
source_url: "https://attack.mitre.org/detectionstrategies/DET0554#AN1532"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1532: Analytic 1532

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1532  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Use of hcitool, bluetoothctl, or rfcomm to initialize Bluetooth connection paired with recent file reads by the same user or session.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1532](https://attack.mitre.org/detectionstrategies/DET0554#AN1532)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
