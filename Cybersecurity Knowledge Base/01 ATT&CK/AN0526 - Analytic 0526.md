---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0526"
source_url: "https://attack.mitre.org/detectionstrategies/DET0185#AN0526"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0526: Analytic 0526

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0526  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Use of AWS STS or GCP IAM APIs to request temporary tokens or federation sessions inconsistent with normal account activity, including from unexpected principals or regions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0526](https://attack.mitre.org/detectionstrategies/DET0185#AN0526)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
