---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0597"
source_url: "https://attack.mitre.org/detectionstrategies/DET0213#AN0597"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0597: Analytic 0597

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0597  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Outbound connections from non-network-facing processes repeatedly send similarly sized payloads within uniform time intervals.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0597](https://attack.mitre.org/detectionstrategies/DET0213#AN0597)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
