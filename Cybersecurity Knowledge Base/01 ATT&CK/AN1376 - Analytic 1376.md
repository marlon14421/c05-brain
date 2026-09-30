---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1376"
source_url: "https://attack.mitre.org/detectionstrategies/DET0499#AN1376"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1376: Analytic 1376

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1376  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Establishing network connections on uncommon ports or protocols following C2 disruption or blocking. Often executed by processes that typically exhibit no network activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1376](https://attack.mitre.org/detectionstrategies/DET0499#AN1376)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
