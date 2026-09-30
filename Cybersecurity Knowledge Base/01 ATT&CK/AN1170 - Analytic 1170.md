---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1170"
source_url: "https://attack.mitre.org/detectionstrategies/DET0416#AN1170"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1170: Analytic 1170

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1170  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects usage of FTP, SCP, or TFTP by non-interactive shells or automation scripts transferring large data volumes to untrusted IPs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1170](https://attack.mitre.org/detectionstrategies/DET0416#AN1170)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
