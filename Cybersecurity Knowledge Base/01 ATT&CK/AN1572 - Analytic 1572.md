---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1572"
source_url: "https://attack.mitre.org/detectionstrategies/DET0570#AN1572"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1572: Analytic 1572

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1572  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes such as curl, wget, rclone, or custom scripts executing uploads to cloud storage endpoints. Defender perspective: detect chained events where tar/gzip is executed to compress files followed by HTTPS PUT/POST requests to known storage services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1572](https://attack.mitre.org/detectionstrategies/DET0570#AN1572)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
