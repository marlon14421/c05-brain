---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0288"
source_url: "https://attack.mitre.org/detectionstrategies/DET0104#AN0288"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0288: Analytic 0288

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0288  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects modification of PAM configuration files, unauthorized new PAM modules, and suspicious process execution accessing PAM-related binaries. Correlates file modification events in /etc/pam.d/ with process execution of unauthorized binaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0288](https://attack.mitre.org/detectionstrategies/DET0104#AN0288)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
