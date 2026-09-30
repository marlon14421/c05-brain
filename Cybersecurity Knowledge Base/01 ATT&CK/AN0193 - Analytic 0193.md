---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0193"
source_url: "https://attack.mitre.org/detectionstrategies/DET0070#AN0193"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0193: Analytic 0193

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0193  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Phishing delivered via SaaS services (chat, collaboration platforms) where messages contain malicious URLs or attachments. Detect anomalous link clicks, suspicious file uploads, or token misuse after SaaS-based phishing attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0193](https://attack.mitre.org/detectionstrategies/DET0070#AN0193)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
