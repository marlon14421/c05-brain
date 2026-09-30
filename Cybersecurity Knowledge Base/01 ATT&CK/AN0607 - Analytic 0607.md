---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0607"
source_url: "https://attack.mitre.org/detectionstrategies/DET0216#AN0607"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0607: Analytic 0607

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0607  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection focuses on unauthorized modification of Mach-O binaries to include LC_LOAD_DYLIB headers pointing to malicious dylibs. Behavior is identified via a chain of file metadata changes, removal of code signatures, and subsequent anomalous dylib loads at runtime. Correlation of file changes with lack of authorized updates and process memory mapping of unrecognized or unsigned libraries is crucial.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0607](https://attack.mitre.org/detectionstrategies/DET0216#AN0607)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
