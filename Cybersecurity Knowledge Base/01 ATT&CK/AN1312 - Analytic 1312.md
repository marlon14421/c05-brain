---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1312"
source_url: "https://attack.mitre.org/detectionstrategies/DET0476#AN1312"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1312: Analytic 1312

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1312  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Correlates unusual auto-forwarding rule creation via Exchange Web Services or Outlook rules engine, presence of X-MS-Exchange-Organization-AutoForwarded headers, and logon session anomalies from abnormal IPs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1312](https://attack.mitre.org/detectionstrategies/DET0476#AN1312)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
