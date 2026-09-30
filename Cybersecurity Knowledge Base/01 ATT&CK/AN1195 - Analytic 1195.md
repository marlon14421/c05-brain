---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1195"
source_url: "https://attack.mitre.org/detectionstrategies/DET0427#AN1195"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1195: Analytic 1195

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1195  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unauthorized modification of service-related registry keys such as ImagePath, FailureCommand, ServiceDll, or Performance/Parameters keys. Defender correlates registry modifications, anomalous service metadata changes, and subsequent service process executions that deviate from baseline configurations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1195](https://attack.mitre.org/detectionstrategies/DET0427#AN1195)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
