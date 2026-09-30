---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1040"
source_url: "https://attack.mitre.org/detectionstrategies/DET0370#AN1040"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1040: Analytic 1040

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1040  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of file enumeration commands (e.g., 'dir', 'tree') from non-standard processes or unusual user contexts, followed by recursive directory traversal or access to sensitive locations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1040](https://attack.mitre.org/detectionstrategies/DET0370#AN1040)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
