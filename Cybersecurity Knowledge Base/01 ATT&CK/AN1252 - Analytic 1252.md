---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1252"
source_url: "https://attack.mitre.org/detectionstrategies/DET0455#AN1252"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1252: Analytic 1252

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1252  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects behavioral chains where PowerShell is launched with encoded commands, unusual parent processes, or suspicious modules loaded, potentially followed by network connections or child process spawning. Supports detection of both direct (powershell.exe) and indirect (.NET automation) invocations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1252](https://attack.mitre.org/detectionstrategies/DET0455#AN1252)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
