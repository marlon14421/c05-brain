---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0051"
source_url: "https://attack.mitre.org/detectionstrategies/DET0017#AN0051"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0051: Analytic 0051

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0051  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlated modification of AppCompat registry keys and execution of sdbinst.exe to install custom shim databases. Followed by DLL injection via shim behavior into target application processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0051](https://attack.mitre.org/detectionstrategies/DET0017#AN0051)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
