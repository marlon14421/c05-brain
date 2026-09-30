---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2031"
source_url: "https://attack.mitre.org/detectionstrategies/DET0898#AN2031"
created: "2025-10-23"
modified: "2025-10-24"
---
# AN2031: Analytic 2031

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2031  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detection of HTTP outbound requests with inconsistent or spoofed User-Agent headers from command-line tools (e.g., curl, wget, python requests) following interactive user shells or scheduled jobs outside of normal user session behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2031](https://attack.mitre.org/detectionstrategies/DET0898#AN2031)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
