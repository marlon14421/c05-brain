---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2043"
source_url: "https://attack.mitre.org/detectionstrategies/DET0901#AN2043"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2043: Analytic 2043

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2043  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects processes or users modifying Windows Defender Firewall profiles, policies, or rules followed by measurable network exposure changes. Correlates firewall management execution, registry/policy mutation, service state changes, and subsequent inbound or outbound connectivity inconsistent with baseline administration.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2043](https://attack.mitre.org/detectionstrategies/DET0901#AN2043)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
