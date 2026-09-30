---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1288"
source_url: "https://attack.mitre.org/detectionstrategies/DET0466#AN1288"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1288: Analytic 1288

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1288  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of Microsoft-signed scripts (e.g., pubprn.vbs, installutil.exe, wscript.exe, cscript.exe) used to proxy execution of untrusted or external binaries. Behavior is detected through command-line process lineage, child process spawning, and unsigned payload execution from signed parent.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1288](https://attack.mitre.org/detectionstrategies/DET0466#AN1288)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
