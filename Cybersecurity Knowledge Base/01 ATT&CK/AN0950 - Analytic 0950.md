---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0950"
source_url: "https://attack.mitre.org/detectionstrategies/DET0336#AN0950"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0950: Analytic 0950

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0950  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects modification of system or application binaries by monitoring /usr/bin, /bin, and other privileged directories. Correlates file integrity monitoring (FIM) events with unexpected process executions or service restarts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0950](https://attack.mitre.org/detectionstrategies/DET0336#AN0950)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
