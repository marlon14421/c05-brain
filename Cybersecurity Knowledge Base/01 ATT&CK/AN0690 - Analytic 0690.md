---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0690"
source_url: "https://attack.mitre.org/detectionstrategies/DET0247#AN0690"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0690: Analytic 0690

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0690  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects creation of cloud instances, services, or resources in normally unused or unsupported regions, especially following initial account access or credential use from known regions. Correlates resource provisioning across regions with absence of historical usage and alerting from standard logging services (e.g., GuardDuty not enabled in that region).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0690](https://attack.mitre.org/detectionstrategies/DET0247#AN0690)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
