---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1271"
source_url: "https://attack.mitre.org/detectionstrategies/DET0461#AN1271"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1271: Analytic 1271

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1271  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Anomalous creation or mounting of hidden partitions or virtual file systems. Defender view: detection of registry modifications linked to non-standard file systems, suspicious disk I/O patterns, or bootkit-like behavior where hidden volumes are accessed outside normal file system APIs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1271](https://attack.mitre.org/detectionstrategies/DET0461#AN1271)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
