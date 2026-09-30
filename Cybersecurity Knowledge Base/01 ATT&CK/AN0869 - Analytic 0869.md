---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0869"
source_url: "https://attack.mitre.org/detectionstrategies/DET0311#AN0869"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0869: Analytic 0869

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0869  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Monitoring for discrepancies between system daemon/service state and reported health messages (e.g., syslog shows AV/IDS daemon stopped, but spoofed messages claim it is still running). Detects userland processes impersonating AV/IDS command-line outputs or modifying log forwarding configurations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0869](https://attack.mitre.org/detectionstrategies/DET0311#AN0869)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
