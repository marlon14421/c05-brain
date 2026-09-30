---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1428"
source_url: "https://attack.mitre.org/detectionstrategies/DET0516#AN1428"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1428: Analytic 1428

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1428  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects the execution of scripting or command interpreters (e.g., powershell.exe, cmd.exe, wscript.exe) outside expected administrative time windows or from abnormal user contexts, often followed by encoded/obfuscated arguments or secondary execution events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1428](https://attack.mitre.org/detectionstrategies/DET0516#AN1428)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
