---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1095"
source_url: "https://attack.mitre.org/detectionstrategies/DET0389#AN1095"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1095: Analytic 1095

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1095  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects DLL injection through correlation of memory allocation and writing to remote process memory (e.g., VirtualAllocEx, WriteProcessMemory), followed by remote thread creation (e.g., CreateRemoteThread) that loads a suspicious or unsigned DLL using LoadLibrary or reflective loading.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1095](https://attack.mitre.org/detectionstrategies/DET0389#AN1095)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
