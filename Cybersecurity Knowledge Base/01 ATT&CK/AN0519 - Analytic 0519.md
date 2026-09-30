---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0519"
source_url: "https://attack.mitre.org/detectionstrategies/DET0183#AN0519"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0519: Analytic 0519

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0519  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Identify lateral transfer via datastore file uploads or internal scp/ssh sessions that result in new VMX/VMDK or script files. Correlate transfer with VM execution or datastore modification.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0519](https://attack.mitre.org/detectionstrategies/DET0183#AN0519)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
