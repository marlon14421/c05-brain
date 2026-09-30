---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1247"
source_url: "https://attack.mitre.org/detectionstrategies/DET0452#AN1247"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1247: Analytic 1247

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1247  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detection monitors extended attribute manipulation (xattr) to strip quarantine or trust metadata, anomalous installation of root certificates in /etc/ssl or /usr/local/share/ca-certificates, and unauthorized modification of system trust stores. Correlates with unexpected process execution involving package managers or custom certificate utilities.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1247](https://attack.mitre.org/detectionstrategies/DET0452#AN1247)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
