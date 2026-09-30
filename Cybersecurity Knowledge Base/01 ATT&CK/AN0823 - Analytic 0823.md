---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0823"
source_url: "https://attack.mitre.org/detectionstrategies/DET0296#AN0823"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0823: Analytic 0823

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0823  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious DNS/ARP poisoning attempts, unauthorized modifications to registry/network configuration, or abnormal TLS downgrade activity. Correlates changes in system configuration with subsequent unusual network flows or authentication events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0823](https://attack.mitre.org/detectionstrategies/DET0296#AN0823)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
