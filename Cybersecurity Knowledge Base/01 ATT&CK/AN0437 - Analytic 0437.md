---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0437"
source_url: "https://attack.mitre.org/detectionstrategies/DET0153#AN0437"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0437: Analytic 0437

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0437  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes such as curl, wget, or custom scripts initiating POST requests to webhook endpoints with encoded or bulk data. Defender perspective: abnormal chaining of file compression or access followed by outbound data to webhook URLs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0437](https://attack.mitre.org/detectionstrategies/DET0153#AN0437)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
