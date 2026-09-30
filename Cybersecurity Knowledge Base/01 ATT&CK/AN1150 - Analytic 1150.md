---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1150"
source_url: "https://attack.mitre.org/detectionstrategies/DET0411#AN1150"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1150: Analytic 1150

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1150  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Monitor unified logs for manipulation of proxy configurations, DNS resolution, or filtering rules. Adversaries may redirect responses or use trusted domains that later resolve to malicious C2 infrastructure.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1150](https://attack.mitre.org/detectionstrategies/DET0411#AN1150)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
