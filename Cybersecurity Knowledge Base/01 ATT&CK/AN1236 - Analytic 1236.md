---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1236"
source_url: "https://attack.mitre.org/detectionstrategies/DET0447#AN1236"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1236: Analytic 1236

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1236  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Local user accounts are created via binaries like 'useradd', 'adduser', or by editing passwd/shadow. Behavior chain includes execution of user management binaries or modification of user database files.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1236](https://attack.mitre.org/detectionstrategies/DET0447#AN1236)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
