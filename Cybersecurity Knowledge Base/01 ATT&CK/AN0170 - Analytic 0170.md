---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0170"
source_url: "https://attack.mitre.org/detectionstrategies/DET0061#AN0170"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0170: Analytic 0170

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0170  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects modification of registry keys used for default file handlers, followed by anomalous process execution from user-initiated file opens. This includes tracking changes under HKCU and HKCR for file extension mappings, and correlating them with new or suspicious handler paths launching unusual child processes (e.g., PowerShell, cmd, wscript).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0170](https://attack.mitre.org/detectionstrategies/DET0061#AN0170)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
