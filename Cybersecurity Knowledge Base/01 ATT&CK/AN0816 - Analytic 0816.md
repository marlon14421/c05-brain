---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0816"
source_url: "https://attack.mitre.org/detectionstrategies/DET0293#AN0816"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0816: Analytic 0816

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0816  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects API calls registering or updating hybrid identity connectors, modification of cloud-to-on-premises federation trust, and unusual token issuance logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0816](https://attack.mitre.org/detectionstrategies/DET0293#AN0816)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
