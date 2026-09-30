---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1372"
source_url: "https://attack.mitre.org/detectionstrategies/DET0497#AN1372"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1372: Analytic 1372

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1372  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Correlates control-plane API actions disabling cloud-native monitoring or sensor agents (CloudTrail, GuardDuty, Security Hub, Defender, monitoring agents), role abuse preceding disablement, or instance agent uninstall events

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1372](https://attack.mitre.org/detectionstrategies/DET0497#AN1372)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
