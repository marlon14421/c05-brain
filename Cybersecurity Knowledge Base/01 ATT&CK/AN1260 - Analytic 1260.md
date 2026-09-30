---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1260"
source_url: "https://attack.mitre.org/detectionstrategies/DET0458#AN1260"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1260: Analytic 1260

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1260  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Adversary adds federated identity provider (IdP) or modifies tenant domain authentication from Managed to Federated. Detected via API, PowerShell, or Admin Portal through federation events like `Set domain authentication`, `Add federated identity provider`, or `Update-MsolFederatedDomain`.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1260](https://attack.mitre.org/detectionstrategies/DET0458#AN1260)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
