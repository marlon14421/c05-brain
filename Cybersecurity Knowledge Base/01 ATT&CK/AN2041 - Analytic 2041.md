---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2041"
source_url: "https://attack.mitre.org/detectionstrategies/DET0900#AN2041"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2041: Analytic 2041

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2041  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects exploitation of cloud-native security boundaries or management components followed by disabled logging, detached agents, changed security groups, policy bypass, or telemetry suppression. Correlates suspicious API activity with reduced control coverage.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2041](https://attack.mitre.org/detectionstrategies/DET0900#AN2041)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
