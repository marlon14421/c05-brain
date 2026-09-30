---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0683"
source_url: "https://attack.mitre.org/detectionstrategies/DET0245#AN0683"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0683: Analytic 0683

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0683  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor call log records from corporate devices for unusual or unauthorized numbers, especially repeated calls to/from known malicious phone numbers. Correlate with subsequent system events (e.g., browser navigation, remote management tool execution).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0683](https://attack.mitre.org/detectionstrategies/DET0245#AN0683)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
