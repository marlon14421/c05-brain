---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0235"
source_url: "https://attack.mitre.org/detectionstrategies/DET0085#AN0235"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0235: Analytic 0235

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0235  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

An adversary running with SYSTEM-level privileges executes commands or accesses registry keys to dump the SAM hive or directly reads sensitive local files from the config directory. This behavior often involves sequential access to HKLM\SAM, HKLM\SYSTEM, and creation of .save or .dmp files, enabling offline hash extraction.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0235](https://attack.mitre.org/detectionstrategies/DET0085#AN0235)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
