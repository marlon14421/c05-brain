---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1637"
source_url: "https://attack.mitre.org/detectionstrategies/DET0595#AN1637"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1637: Analytic 1637

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1637  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detects adversary abuse of SaaS platform vulnerabilities to bypass logging, monitoring, or consent boundaries. Defender perspective focuses on abnormal application integration events, missing audit logs, or API calls from unauthorized service principals that align with exploitation attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1637](https://attack.mitre.org/detectionstrategies/DET0595#AN1637)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
