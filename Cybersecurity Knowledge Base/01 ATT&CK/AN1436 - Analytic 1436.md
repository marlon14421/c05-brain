---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1436"
source_url: "https://attack.mitre.org/detectionstrategies/DET0519#AN1436"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1436: Analytic 1436

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1436  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversaries inject VBA macros into Office templates such as Normal.dotm or Personal.xlsb or redirect Office template load path via registry key (GlobalDotName) to gain persistence. Template macros trigger execution of malicious code on application startup.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1436](https://attack.mitre.org/detectionstrategies/DET0519#AN1436)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
