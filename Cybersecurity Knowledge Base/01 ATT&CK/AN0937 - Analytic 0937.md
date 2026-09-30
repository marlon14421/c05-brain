---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0937"
source_url: "https://attack.mitre.org/detectionstrategies/DET0329#AN0937"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0937: Analytic 0937

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0937  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Cloud API calls disabling snapshot scheduling, backup policies, versioning, followed by DeleteSnapshot/DeleteVolume operations

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0937](https://attack.mitre.org/detectionstrategies/DET0329#AN0937)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
