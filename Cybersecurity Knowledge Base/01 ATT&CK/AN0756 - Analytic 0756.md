---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0756"
source_url: "https://attack.mitre.org/detectionstrategies/DET0270#AN0756"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0756: Analytic 0756

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0756  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Adversary modifies tenant policy through changes to federation configuration, trust settings, or identity provider additions in Microsoft 365/AzureAD via Portal, PowerShell, or Graph API. Includes setting authentication to federated or updating federated domains.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0756](https://attack.mitre.org/detectionstrategies/DET0270#AN0756)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
