---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1124"
source_url: "https://attack.mitre.org/detectionstrategies/DET0400#AN1124"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1124: Analytic 1124

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1124  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects clients issuing DNS queries with high volume, long subdomain lengths, encoded payload patterns, or to known malicious infrastructure; indicative of DNS-based C2 channels.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1124](https://attack.mitre.org/detectionstrategies/DET0400#AN1124)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
