---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1146"
source_url: "https://attack.mitre.org/detectionstrategies/DET0410#AN1146"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1146: Analytic 1146

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1146  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Unusual access or copying of files from mounted network drives (e.g., NFS, CIFS/SMB) by user shells or scripts followed by large data transfer.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1146](https://attack.mitre.org/detectionstrategies/DET0410#AN1146)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
