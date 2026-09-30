---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1064"
source_url: "https://attack.mitre.org/detectionstrategies/DET0378#AN1064"
created: "2025-10-21"
modified: "2025-10-29"
---
# AN1064: Analytic 1064

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1064  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlates script execution or suspicious parent processes with creation or modification of encoded, compressed, or encrypted file formats (e.g., .zip, .7z, .enc) and abnormal command-line syntax or PowerShell obfuscation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1064](https://attack.mitre.org/detectionstrategies/DET0378#AN1064)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
