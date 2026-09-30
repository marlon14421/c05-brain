---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1388"
source_url: "https://attack.mitre.org/detectionstrategies/DET0502#AN1388"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1388: Analytic 1388

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1388  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Malicious macros or embedded objects hidden within Office documents by renaming streams or using hidden OLE objects. Defender view: detection of hidden macro streams or objects in documents correlated with anomalous execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1388](https://attack.mitre.org/detectionstrategies/DET0502#AN1388)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
