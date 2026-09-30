---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0648"
source_url: "https://attack.mitre.org/detectionstrategies/DET0234#AN0648"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0648: Analytic 0648

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0648  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes accessing LSASS memory or SAM registry hives outside of trusted security tools, often followed by file creation or lateral movement. Detects unauthorized access to sensitive OS subsystems for credential extraction.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0648](https://attack.mitre.org/detectionstrategies/DET0234#AN0648)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
