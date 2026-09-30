---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0935"
source_url: "https://attack.mitre.org/detectionstrategies/DET0329#AN0935"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0935: Analytic 0935

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0935  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi shell or vim-cmd execution that deletes all VM snapshots using vmsvc/snapshot.removeall or rm on snapshot paths

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0935](https://attack.mitre.org/detectionstrategies/DET0329#AN0935)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
