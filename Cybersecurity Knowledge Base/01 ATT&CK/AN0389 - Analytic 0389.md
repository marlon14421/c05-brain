---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0389"
source_url: "https://attack.mitre.org/detectionstrategies/DET0139#AN0389"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0389: Analytic 0389

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0389  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects credential harvesting via userland API hooking (e.g., SetWindowsHookEx, IAT, or inline patching) by correlating memory modifications with hook installation functions and suspicious module loads in credential-sensitive processes like lsass.exe, explorer.exe, or winlogon.exe.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0389](https://attack.mitre.org/detectionstrategies/DET0139#AN0389)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
