---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0758"
source_url: "https://attack.mitre.org/detectionstrategies/DET0272#AN0758"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0758: Analytic 0758

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0758  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects unauthorized modification of network device authentication by correlating OS image file changes, checksum mismatches, or memory verification failures with anomalous authentication events. Focus is on behaviors where patched images introduce hardcoded passwords or bypass native authentication.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0758](https://attack.mitre.org/detectionstrategies/DET0272#AN0758)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
