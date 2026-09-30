---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0009"
source_url: "https://attack.mitre.org/detectionstrategies/DET0004#AN0009"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0009: Analytic 0009

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0009  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Abnormal modification of the PATH environment variable or registry keys controlling system paths, combined with execution of binaries named after legitimate system tools from user-writable directories. Defender correlates registry modifications, file creation of suspicious binaries, and process execution paths inconsistent with baseline system directories.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0009](https://attack.mitre.org/detectionstrategies/DET0004#AN0009)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
