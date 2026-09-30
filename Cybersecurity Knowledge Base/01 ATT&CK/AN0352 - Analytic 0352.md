---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0352"
source_url: "https://attack.mitre.org/detectionstrategies/DET0126#AN0352"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0352: Analytic 0352

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0352  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Abuse of cloud metadata APIs or CLI to push SSH public keys to authorized_keys of virtual machines.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0352](https://attack.mitre.org/detectionstrategies/DET0126#AN0352)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
