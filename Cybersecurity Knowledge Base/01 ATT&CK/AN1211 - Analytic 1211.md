---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1211"
source_url: "https://attack.mitre.org/detectionstrategies/DET0436#AN1211"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1211: Analytic 1211

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1211  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Modification or replacement of service executables due to weak file or directory permissions. Defender observes file writes to service binary paths, unexpected modifications of executables associated with registered services, and subsequent service execution of attacker-supplied binaries under elevated permissions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1211](https://attack.mitre.org/detectionstrategies/DET0436#AN1211)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
