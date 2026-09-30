---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1335"
source_url: "https://attack.mitre.org/detectionstrategies/DET0486#AN1335"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1335: Analytic 1335

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1335  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Identifies abuse of odbcconf.exe to execute malicious DLLs using the REGSVR command flag. Behavior chain: (1) Process creation of odbcconf.exe with /REGSVR or /A {REGSVR ...} arguments → (2) DLL load by odbcconf.exe of non-standard or unsigned modules → (3) Optional follow-on process creation or network activity from loaded DLL.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1335](https://attack.mitre.org/detectionstrategies/DET0486#AN1335)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
