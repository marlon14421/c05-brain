---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1070"
source_url: "https://attack.mitre.org/detectionstrategies/DET0380#AN1070"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1070: Analytic 1070

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1070  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversaries collecting local files via PowerShell, WMI, or direct file API calls often include recursive file listings, targeted file reads, and temporary file staging.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1070](https://attack.mitre.org/detectionstrategies/DET0380#AN1070)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
