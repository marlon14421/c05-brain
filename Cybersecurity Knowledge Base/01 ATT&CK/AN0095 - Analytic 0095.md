---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0095"
source_url: "https://attack.mitre.org/detectionstrategies/DET0034#AN0095"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0095: Analytic 0095

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0095  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Identifies adversary behavior that launches commands or invokes APIs to enumerate active processes (e.g., tasklist.exe, Get-Process, or CreateToolhelp32Snapshot). Detects execution combined with parent process lineage, network session context, or remote origin.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0095](https://attack.mitre.org/detectionstrategies/DET0034#AN0095)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
