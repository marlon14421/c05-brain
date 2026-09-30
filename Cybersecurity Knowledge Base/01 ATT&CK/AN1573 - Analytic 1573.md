---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1573"
source_url: "https://attack.mitre.org/detectionstrategies/DET0570#AN1573"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1573: Analytic 1573

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1573  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Applications or scripts invoking cloud storage APIs (Dropbox sync, iCloud, Google Drive client) in unexpected contexts. Defender perspective: detect sensitive file reads by non-standard applications followed by unusual encrypted uploads to external cloud storage domains.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1573](https://attack.mitre.org/detectionstrategies/DET0570#AN1573)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
