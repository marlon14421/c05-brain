---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0053"
source_url: "https://attack.mitre.org/detectionstrategies/DET0018#AN0053"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0053: Analytic 0053

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0053  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

A process loads a shared object (.so) via dlopen/LD_PRELOAD/open from non-standard or temporary locations (e.g., /tmp, /dev/shm), especially shortly after that .so is written or fetched, or linked via manipulated environment variables (LD_PRELOAD/LD_LIBRARY_PATH).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0053](https://attack.mitre.org/detectionstrategies/DET0018#AN0053)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
