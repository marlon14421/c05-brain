---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1400"
source_url: "https://attack.mitre.org/detectionstrategies/DET0508#AN1400"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1400: Analytic 1400

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1400  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects ptrace- or memfd-based process injection through audit logs capturing system calls (e.g., ptrace, mmap) targeting running processes along with suspicious file descriptors or memory writes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1400](https://attack.mitre.org/detectionstrategies/DET0508#AN1400)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
