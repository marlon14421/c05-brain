---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0184"
source_url: "https://attack.mitre.org/detectionstrategies/DET0068#AN0184"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0184: Analytic 0184

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0184  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary installs or modifies IIS components (ISAPI filters, extensions, or modules) using DLL files registered via configuration changes or administrative tools like AppCmd.exe. These components intercept or manipulate HTTP requests/responses for persistence or C2.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0184](https://attack.mitre.org/detectionstrategies/DET0068#AN0184)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
