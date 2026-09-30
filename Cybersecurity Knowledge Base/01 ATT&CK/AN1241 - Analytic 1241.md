---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1241"
source_url: "https://attack.mitre.org/detectionstrategies/DET0448#AN1241"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1241: Analytic 1241

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1241  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects the redirection of syscall execution flow via modification of VDSO code stubs or GOT entries to load and execute a malicious shared object through mmap and ptrace.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1241](https://attack.mitre.org/detectionstrategies/DET0448#AN1241)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
