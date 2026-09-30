---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1350"
source_url: "https://attack.mitre.org/detectionstrategies/DET0488#AN1350"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1350: Analytic 1350

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1350  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Behavioral chain: (1) delegated administration offers/relationships created or modified by partner tenants; (2) mailbox delegation/impersonation enabled; (3) follow-on access from partner IPs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1350](https://attack.mitre.org/detectionstrategies/DET0488#AN1350)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
