---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0871"
source_url: "https://attack.mitre.org/detectionstrategies/DET0312#AN0871"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0871: Analytic 0871

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0871  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Multi-event correlation of Registry creation under Active Setup with anomalous execution of processes at user logon. Behavioral patterns include creation/modification of HKLM Active Setup keys with non-standard StubPath values, followed by process execution from uncommon paths, unsigned binaries, or unusual parent-child lineage post-user login.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0871](https://attack.mitre.org/detectionstrategies/DET0312#AN0871)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
