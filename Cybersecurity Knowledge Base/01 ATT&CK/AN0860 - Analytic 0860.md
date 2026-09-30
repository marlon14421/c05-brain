---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0860"
source_url: "https://attack.mitre.org/detectionstrategies/DET0307#AN0860"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0860: Analytic 0860

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0860  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Access to local credential/config files (e.g., ~/.aws/credentials) followed by metadata API calls or cloud role assumptions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0860](https://attack.mitre.org/detectionstrategies/DET0307#AN0860)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
