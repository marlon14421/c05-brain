---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1597"
source_url: "https://attack.mitre.org/detectionstrategies/DET0579#AN1597"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1597: Analytic 1597

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1597  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detect loading or inspection of kernel extensions (kextstat, kextfind) and file access to /System/Library/Extensions/. Monitor unexpected usage of these utilities by non-administrative users or scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1597](https://attack.mitre.org/detectionstrategies/DET0579#AN1597)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
