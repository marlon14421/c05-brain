---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0209"
source_url: "https://attack.mitre.org/detectionstrategies/DET0076#AN0209"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0209: Analytic 0209

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0209  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects execution of VB-based scripts or macros (VBS/VBA/VBScript) through cscript.exe/wscript.exe, Office-based process chains, or HTA usage. Focuses on chained behavior: Office or HTML container spawns script host > script host spawns PowerShell, network connections, or process injection.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0209](https://attack.mitre.org/detectionstrategies/DET0076#AN0209)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
