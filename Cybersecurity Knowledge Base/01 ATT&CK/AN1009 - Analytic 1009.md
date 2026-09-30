---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1009"
source_url: "https://attack.mitre.org/detectionstrategies/DET0355#AN1009"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1009: Analytic 1009

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1009  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Monitor mail server logs (e.g., Postfix, Sendmail) for excessive connections or inbound message counts targeting a single recipient. Correlate with repetitive attachment storage in /var/mail or /var/spool/mail directories.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1009](https://attack.mitre.org/detectionstrategies/DET0355#AN1009)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
