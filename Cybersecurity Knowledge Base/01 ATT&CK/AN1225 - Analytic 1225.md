---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1225"
source_url: "https://attack.mitre.org/detectionstrategies/DET0444#AN1225"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1225: Analytic 1225

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1225  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious usage of common application-layer protocols (e.g., HTTP, HTTPS, DNS, SMB) by abnormal processes, with high outbound byte counts or irregular ports, possibly indicating command and control or data exfiltration.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1225](https://attack.mitre.org/detectionstrategies/DET0444#AN1225)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
