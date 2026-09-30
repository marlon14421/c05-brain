---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0900"
source_url: "https://attack.mitre.org/detectionstrategies/DET0319#AN0900"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0900: Analytic 0900

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0900  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Adversaries use cloud API, CLI, or console to create IAM users or roles. Initial CreateUser is followed by policy/role attachment. Detection monitors temporal chains involving IAM:CreateUser, AttachUserPolicy, and credential generation, especially from automation or foreign IP ranges.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0900](https://attack.mitre.org/detectionstrategies/DET0319#AN0900)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
