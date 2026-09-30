---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1381"
source_url: "https://attack.mitre.org/detectionstrategies/DET0501#AN1381"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1381: Analytic 1381

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1381  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects compilation activity using csc.exe, ilasm.exe, or msbuild.exe initiated by user-space processes outside typical development environments, followed by execution or network activity from newly written binaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1381](https://attack.mitre.org/detectionstrategies/DET0501#AN1381)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
