---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0878"
source_url: "https://attack.mitre.org/detectionstrategies/DET0314#AN0878"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0878: Analytic 0878

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0878  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects creation of traffic mirroring sessions (e.g., AWS VPC Traffic Mirroring, Azure vTAP) that redirect traffic from critical assets to other virtual instances, often followed by file creation or session establishment.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0878](https://attack.mitre.org/detectionstrategies/DET0314#AN0878)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
