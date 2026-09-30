---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0748"
source_url: "https://attack.mitre.org/detectionstrategies/DET0268#AN0748"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0748: Analytic 0748

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0748  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects adversarial archiving by scripts or binaries calling compression libraries (libzip, zlib, bzip2). Correlates execution of Python, Perl, or compiled binaries with dynamic linking to archiving libraries and creation of compressed files in /tmp or user directories.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0748](https://attack.mitre.org/detectionstrategies/DET0268#AN0748)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
