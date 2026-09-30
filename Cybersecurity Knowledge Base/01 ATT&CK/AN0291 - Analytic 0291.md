---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0291"
source_url: "https://attack.mitre.org/detectionstrategies/DET0104#AN0291"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0291: Analytic 0291

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0291  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects unauthorized changes to IAM authentication configurations such as disabling MFA, creating backdoor access keys, or altering trust policies. Correlates identity policy updates with unusual login behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0291](https://attack.mitre.org/detectionstrategies/DET0104#AN0291)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
