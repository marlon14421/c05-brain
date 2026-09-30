---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0968"
source_url: "https://attack.mitre.org/detectionstrategies/DET0342#AN0968"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0968: Analytic 0968

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0968  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of hh.exe to open a .chm file followed by suspicious child processes or script engine invocation (VBScript, JScript, mshta, powershell). Behavior includes loading a CHM file from untrusted locations, or immediately spawning commands indicative of payload execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0968](https://attack.mitre.org/detectionstrategies/DET0342#AN0968)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
