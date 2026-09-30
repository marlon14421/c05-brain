---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1480"
source_url: "https://attack.mitre.org/detectionstrategies/DET0537#AN1480"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1480: Analytic 1480

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1480  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

1) New or updated software is delivered/installed from atypical sources or with signature/hash mismatches; 2) installer/updater writes binaries to unexpected paths or replaces existing signed files; 3) first run causes unsigned/abnormally signed modules to load or child processes to execute, optionally followed by network egress to new destinations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1480](https://attack.mitre.org/detectionstrategies/DET0537#AN1480)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
