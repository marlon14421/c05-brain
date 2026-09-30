---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1626"
source_url: "https://attack.mitre.org/detectionstrategies/DET0591#AN1626"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1626: Analytic 1626

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1626  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects attempts to modify file timestamps via API usage (e.g., `SetFileTime`), CLI tools (e.g., `w32tm`, PowerShell), or double-timestomp behavior where $SI and $FN timestamps are mismatched or reverted.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1626](https://attack.mitre.org/detectionstrategies/DET0591#AN1626)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
