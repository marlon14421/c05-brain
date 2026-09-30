---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0741"
source_url: "https://attack.mitre.org/detectionstrategies/DET0267#AN0741"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0741: Analytic 0741

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0741  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Persistent high CPU utilization combined with suspicious command-line execution (e.g., mining tools or obfuscated scripts) and outbound connections to mining/proxy networks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0741](https://attack.mitre.org/detectionstrategies/DET0267#AN0741)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
