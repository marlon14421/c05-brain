---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0087"
source_url: "https://attack.mitre.org/detectionstrategies/DET0030#AN0087"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0087: Analytic 0087

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0087  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects modifications to IAM conditions or policies that alter authentication behavior, such as adding permissive trusted IPs, removing MFA requirements, or changing regional access restrictions. Behavioral detection focuses on anomalous policy updates tied to privileged accounts and subsequent suspicious logon activity from previously blocked regions or devices.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0087](https://attack.mitre.org/detectionstrategies/DET0030#AN0087)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
