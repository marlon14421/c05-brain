---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0385"
source_url: "https://attack.mitre.org/detectionstrategies/DET0137#AN0385"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0385: Analytic 0385

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0385  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes invoking destructive commands (dd, shred, wipe) with raw device targets (e.g., /dev/sda, /dev/nvme0n1). Detect direct writes to disk partitions and abnormal superblock or bootloader modifications. Correlate shell execution with subsequent block device I/O.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0385](https://attack.mitre.org/detectionstrategies/DET0137#AN0385)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
