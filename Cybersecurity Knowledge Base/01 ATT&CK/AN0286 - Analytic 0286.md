---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0286"
source_url: "https://attack.mitre.org/detectionstrategies/DET0103#AN0286"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0286: Analytic 0286

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0286  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects network share disconnection attempts using command-line tools like `net use /delete`, PowerShell `Remove-SmbMapping`, and correlation with process lineage and SMB session teardown activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0286](https://attack.mitre.org/detectionstrategies/DET0103#AN0286)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
