---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0732"
source_url: "https://attack.mitre.org/detectionstrategies/DET0263#AN0732"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0732: Analytic 0732

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0732  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Anomalous or bulk download activity from private or restricted repositories by non-developer or privileged accounts, often preceded by unusual login behavior (e.g., unfamiliar geo, OAuth token use, elevated API rate).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0732](https://attack.mitre.org/detectionstrategies/DET0263#AN0732)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
