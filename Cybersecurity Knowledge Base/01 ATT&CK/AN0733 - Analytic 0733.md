---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0733"
source_url: "https://attack.mitre.org/detectionstrategies/DET0264#AN0733"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0733: Analytic 0733

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0733  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects JavaScript execution through WSH (wscript.exe, cscript.exe) or HTA (mshta.exe), particularly when spawned from Office macros, web browsers, or abnormal user paths. Correlates script execution with outbound network activity or system modification.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0733](https://attack.mitre.org/detectionstrategies/DET0264#AN0733)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
