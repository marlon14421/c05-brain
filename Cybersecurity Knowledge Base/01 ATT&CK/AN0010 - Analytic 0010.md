---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0010"
source_url: "https://attack.mitre.org/detectionstrategies/DET0004#AN0010"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0010: Analytic 0010

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0010  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

User modification of the $PATH environment variable in shell configuration files or direct runtime PATH changes, followed by execution of binaries from user-controlled directories. Defender observes file edits to ~/.bashrc, ~/.profile, or /etc/paths.d and process execution resolving to unexpected binary locations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0010](https://attack.mitre.org/detectionstrategies/DET0004#AN0010)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
