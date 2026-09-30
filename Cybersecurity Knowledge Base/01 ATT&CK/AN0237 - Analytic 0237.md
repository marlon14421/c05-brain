---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0237"
source_url: "https://attack.mitre.org/detectionstrategies/DET0087#AN0237"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0237: Analytic 0237

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0237  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of processes that load or decode encrypted/encoded files in memory and subsequently execute or inject them, indicating payload unpacking or memory-resident malware.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0237](https://attack.mitre.org/detectionstrategies/DET0087#AN0237)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
