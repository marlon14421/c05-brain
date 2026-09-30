---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1086"
source_url: "https://attack.mitre.org/detectionstrategies/DET0385#AN1086"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1086: Analytic 1086

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1086  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

A process or terminal command outside of standard shell utilities reads the user's .bash_history file. On macOS, unified logs or telemetry tools like EndpointSecurity (ESF) may observe file read APIs or terminal process lineage that shows non-user-initiated access.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1086](https://attack.mitre.org/detectionstrategies/DET0385#AN1086)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
