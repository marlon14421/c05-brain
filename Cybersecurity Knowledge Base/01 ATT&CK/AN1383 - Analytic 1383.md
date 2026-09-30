---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1383"
source_url: "https://attack.mitre.org/detectionstrategies/DET0501#AN1383"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1383: Analytic 1383

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1383  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects non-standard compilation activity via Xcode CLI tools or bundled GCC/MONO packages writing new executable files and executing them outside dev environments (e.g., user Downloads folder).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1383](https://attack.mitre.org/detectionstrategies/DET0501#AN1383)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
