---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0833"
source_url: "https://attack.mitre.org/detectionstrategies/DET0298#AN0833"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0833: Analytic 0833

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0833  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects invocation of macOS-native archiving utilities (zip, ditto, hdiutil) or openssl used for encryption. Correlates execution with archive or encrypted file creation (.zip, .dmg, .tar.gz) in user or temporary directories. Identifies anomalous use of archiving commands by Office applications or daemons.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0833](https://attack.mitre.org/detectionstrategies/DET0298#AN0833)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
