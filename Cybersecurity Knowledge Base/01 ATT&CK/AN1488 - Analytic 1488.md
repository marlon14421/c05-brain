---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1488"
source_url: "https://attack.mitre.org/detectionstrategies/DET0539#AN1488"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1488: Analytic 1488

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1488  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detects anomalous SaaS application integration activity across environments such as Slack, Salesforce, or other enterprise SaaS services. Focus is on unauthorized app additions, unusual permission grants, and persistence through service principal tokens.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1488](https://attack.mitre.org/detectionstrategies/DET0539#AN1488)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
