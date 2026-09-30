---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0702"
source_url: "https://attack.mitre.org/detectionstrategies/DET0254#AN0702"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0702: Analytic 0702

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0702  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for anomalies in transmitted data streams, including mismatched file integrity checks, API interception, or man-in-the-middle modifications. Detect unexpected use of APIs that handle network I/O where transmitted data integrity could be manipulated.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0702](https://attack.mitre.org/detectionstrategies/DET0254#AN0702)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
