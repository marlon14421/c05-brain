---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0840"
source_url: "https://attack.mitre.org/detectionstrategies/DET0300#AN0840"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0840: Analytic 0840

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0840  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Suspicious calls to dlopen(), dlsym(), or mmap with RWX flags in processes that do not typically perform dynamic module loading. Monitor anonymous memory regions executed by user processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0840](https://attack.mitre.org/detectionstrategies/DET0300#AN0840)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
