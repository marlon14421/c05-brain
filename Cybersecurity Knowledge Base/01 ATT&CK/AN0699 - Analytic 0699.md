---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0699"
source_url: "https://attack.mitre.org/detectionstrategies/DET0252#AN0699"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0699: Analytic 0699

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0699  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of `pip.exe`, `npm.cmd`, or MSI installers within user context, followed by script interpreter startup (e.g., python.exe) or PowerShell with unusual child processes or file writes in `%APPDATA%`, `%TEMP%`, or `%LOCALAPPDATA%`. Defender correlates command-line install tools with Sysmon and Event Logs to trace downstream behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0699](https://attack.mitre.org/detectionstrategies/DET0252#AN0699)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
