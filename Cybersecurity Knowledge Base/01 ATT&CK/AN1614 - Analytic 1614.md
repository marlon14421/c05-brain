---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1614"
source_url: "https://attack.mitre.org/detectionstrategies/DET0587#AN1614"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1614: Analytic 1614

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1614  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection of account enumeration through directory service queries or system utilities accessing account metadata stores, followed by structured enumeration output.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1614](https://attack.mitre.org/detectionstrategies/DET0587#AN1614)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
