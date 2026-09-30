---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0391"
source_url: "https://attack.mitre.org/detectionstrategies/DET0139#AN0391"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0391: Analytic 0391

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0391  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects DYLD_INSERT_LIBRARIES abuse to hook credential-sensitive applications by correlating process spawns with unauthorized library injection and monitoring changes to the __TEXT segment (code) of credential handling binaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0391](https://attack.mitre.org/detectionstrategies/DET0139#AN0391)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
