---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1466"
source_url: "https://attack.mitre.org/detectionstrategies/DET0529#AN1466"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1466: Analytic 1466

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1466  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Userland processes invoking syscall-heavy libraries (libc, glibc) followed by fork, mmap, or ptrace behavior commonly associated with code injection or memory manipulation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1466](https://attack.mitre.org/detectionstrategies/DET0529#AN1466)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
