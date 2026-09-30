---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1447"
source_url: "https://attack.mitre.org/detectionstrategies/DET0523#AN1447"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1447: Analytic 1447

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1447  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects modification of System Integrity Protection (SIP) or code signing enforcement policies through csrutil or kernel variable tampering. Correlates execution of csrutil disable commands with subsequent policy state changes and anomalous unsigned process executions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1447](https://attack.mitre.org/detectionstrategies/DET0523#AN1447)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
