---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1589"
source_url: "https://attack.mitre.org/detectionstrategies/DET0576#AN1589"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1589: Analytic 1589

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1589  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Creation of inbox rules via PowerShell (New-InboxRule) or transport rules using Exchange cmdlets. Correlates user behavior, cmdlet usage, and rule properties.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1589](https://attack.mitre.org/detectionstrategies/DET0576#AN1589)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
