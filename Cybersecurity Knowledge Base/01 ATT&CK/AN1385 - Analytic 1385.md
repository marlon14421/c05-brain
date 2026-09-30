---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1385"
source_url: "https://attack.mitre.org/detectionstrategies/DET0502#AN1385"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1385: Analytic 1385

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1385  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Hidden file creation using leading '.' or file attribute changes with chattr (immutable/hidden flags). Defender view: detect execution of chattr, lsattr anomalies, and unusual hidden files appearing in system directories.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1385](https://attack.mitre.org/detectionstrategies/DET0502#AN1385)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
