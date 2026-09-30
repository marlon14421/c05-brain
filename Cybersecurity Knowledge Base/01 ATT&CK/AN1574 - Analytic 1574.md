---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1574"
source_url: "https://attack.mitre.org/detectionstrategies/DET0570#AN1574"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1574: Analytic 1574

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1574  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Unusual ESXi processes (vmx, hostd) reading datastore files and generating outbound HTTPS traffic toward external cloud storage endpoints. Defender perspective: anomalous datastore activity followed by network transfers to Dropbox, AWS S3, or other storage services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1574](https://attack.mitre.org/detectionstrategies/DET0570#AN1574)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
