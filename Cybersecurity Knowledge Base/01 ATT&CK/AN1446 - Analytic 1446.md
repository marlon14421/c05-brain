---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1446"
source_url: "https://attack.mitre.org/detectionstrategies/DET0523#AN1446"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1446: Analytic 1446

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1446  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitors execution of administrative utilities (e.g., bcdedit.exe) or registry modifications that disable Driver Signature Enforcement (DSE) or enable Test Signing. Correlates command-line activity, registry changes, and subsequent process executions that bypass signing enforcement.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1446](https://attack.mitre.org/detectionstrategies/DET0523#AN1446)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
