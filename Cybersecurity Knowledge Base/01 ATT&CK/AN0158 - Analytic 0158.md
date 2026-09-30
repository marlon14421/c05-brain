---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0158"
source_url: "https://attack.mitre.org/detectionstrategies/DET0058#AN0158"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0158: Analytic 0158

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0158  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of a process or script that accesses a common web service to retrieve content containing obfuscated indicators of a secondary C2 server (dead drop resolver behavior).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0158](https://attack.mitre.org/detectionstrategies/DET0058#AN0158)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
