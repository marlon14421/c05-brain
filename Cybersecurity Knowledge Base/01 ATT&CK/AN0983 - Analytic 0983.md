---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0983"
source_url: "https://attack.mitre.org/detectionstrategies/DET0347#AN0983"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0983: Analytic 0983

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0983  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects processes or binaries executed from trusted directories (e.g., System32) or using trusted names (e.g., svchost.exe) where the metadata, hash, or parent process does not align with legitimate activity patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0983](https://attack.mitre.org/detectionstrategies/DET0347#AN0983)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
