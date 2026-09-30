---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1216"
source_url: "https://attack.mitre.org/detectionstrategies/DET0439#AN1216"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1216: Analytic 1216

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1216  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects the relocation of malicious executables via copy/move actions across suspicious folders (e.g., from Downloads to System32), followed by deletion of the original source or renaming to blend into legitimate binaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1216](https://attack.mitre.org/detectionstrategies/DET0439#AN1216)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
