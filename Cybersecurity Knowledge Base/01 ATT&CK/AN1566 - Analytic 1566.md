---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1566"
source_url: "https://attack.mitre.org/detectionstrategies/DET0567#AN1566"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1566: Analytic 1566

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1566  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Suspicious access to Microsoft Teams chat messages via eDiscovery, Graph API, or export methods after rare or compromised sign-in. Often associated with excessive file access, sensitive content review, or anomaly from expected user behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1566](https://attack.mitre.org/detectionstrategies/DET0567#AN1566)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
