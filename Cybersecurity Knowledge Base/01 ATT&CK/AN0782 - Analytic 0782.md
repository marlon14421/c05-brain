---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0782"
source_url: "https://attack.mitre.org/detectionstrategies/DET0281#AN0782"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0782: Analytic 0782

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0782  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitors for compression tool usage (e.g., 7zip, WinRAR, MakeCab) that follows or precedes file modification, suspicious file types (e.g., .exe, .dll) being compressed, or dropped from self-extracting archives followed by immediate execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0782](https://attack.mitre.org/detectionstrategies/DET0281#AN0782)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
