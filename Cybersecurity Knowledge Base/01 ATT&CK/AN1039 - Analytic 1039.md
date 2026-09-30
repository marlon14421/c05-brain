---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1039"
source_url: "https://attack.mitre.org/detectionstrategies/DET0369#AN1039"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1039: Analytic 1039

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1039  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detect unauthorized `trap` command registrations in shell startup files (e.g., .zprofile, .bash_profile, .zshrc) followed by execution chains during user terminal interaction. Use Unified Logs and EDR telemetry to correlate shell command parsing and process tree anomalies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1039](https://attack.mitre.org/detectionstrategies/DET0369#AN1039)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
