---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1063"
source_url: "https://attack.mitre.org/detectionstrategies/DET0377#AN1063"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1063: Analytic 1063

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1063  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Execution of unsigned kernel extensions (KEXTs), tampering with LaunchDaemons, or userspace hooks into system libraries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1063](https://attack.mitre.org/detectionstrategies/DET0377#AN1063)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
