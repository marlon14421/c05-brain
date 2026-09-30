---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0822"
source_url: "https://attack.mitre.org/detectionstrategies/DET0295#AN0822"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0822: Analytic 0822

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0822  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects hijacking of an existing thread (OpenThread) through a behavioral chain involving thread suspension (SuspendThread), memory modification (VirtualAllocEx + WriteProcessMemory), context manipulation (SetThreadContext), and thread resumption—all within another live process's address space (ResumeThread).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0822](https://attack.mitre.org/detectionstrategies/DET0295#AN0822)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
