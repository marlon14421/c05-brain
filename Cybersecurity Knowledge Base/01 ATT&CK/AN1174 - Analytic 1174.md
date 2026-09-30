---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1174"
source_url: "https://attack.mitre.org/detectionstrategies/DET0417#AN1174"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1174: Analytic 1174

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1174  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor command execution of powercfg.exe with arguments modifying sleep, hibernate, or display timeouts. Abnormal or repeated modifications to power settings outside administrative baselines may indicate persistence attempts. Correlate process creation with registry and system configuration changes to build behavioral chains.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1174](https://attack.mitre.org/detectionstrategies/DET0417#AN1174)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
