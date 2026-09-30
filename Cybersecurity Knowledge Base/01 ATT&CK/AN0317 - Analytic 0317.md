---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0317"
source_url: "https://attack.mitre.org/detectionstrategies/DET0114#AN0317"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0317: Analytic 0317

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0317  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects attempts to enumerate local groups via Net.exe, PowerShell, or native API calls that precede lateral movement or privilege abuse.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0317](https://attack.mitre.org/detectionstrategies/DET0114#AN0317)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
