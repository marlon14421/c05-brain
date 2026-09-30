---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1346"
source_url: "https://attack.mitre.org/detectionstrategies/DET0488#AN1346"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1346: Analytic 1346

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1346  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Behavioral chain: (1) third-party interactive login or mobileconfig-based device enrollment; (2) privilege use or admin group change; (3) lateral movement mounts/ssh. Correlate unified logs and network telemetry.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1346](https://attack.mitre.org/detectionstrategies/DET0488#AN1346)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
