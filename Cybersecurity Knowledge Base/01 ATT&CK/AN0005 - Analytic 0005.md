---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0005"
source_url: "https://attack.mitre.org/detectionstrategies/DET0002#AN0005"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0005: Analytic 0005

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0005  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects pub/sub traffic over unusual ports, high-frequency topic publications, and connections to known-bad or dynamic broker endpoints outside allowlisted infrastructure.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0005](https://attack.mitre.org/detectionstrategies/DET0002#AN0005)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
