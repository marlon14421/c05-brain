---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0370"
source_url: "https://attack.mitre.org/detectionstrategies/DET0131#AN0370"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0370: Analytic 0370

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0370  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects access to cloud APIs or CLI tools to move or sync files from sensitive buckets to external endpoints using protocols like HTTPS or S3 APIs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0370](https://attack.mitre.org/detectionstrategies/DET0131#AN0370)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
