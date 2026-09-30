---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0749"
source_url: "https://attack.mitre.org/detectionstrategies/DET0268#AN0749"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0749: Analytic 0749

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0749  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects malicious archiving via system or third-party libraries (libz, libarchive) invoked by Python, Swift, or Objective-C binaries. Correlates unified logs of library loads with creation of compressed or encrypted archives (.zip, .gz, .bz2, .dmg).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0749](https://attack.mitre.org/detectionstrategies/DET0268#AN0749)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
