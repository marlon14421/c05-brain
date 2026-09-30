---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0047"
source_url: "https://attack.mitre.org/detectionstrategies/DET0015#AN0047"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0047: Analytic 0047

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0047  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects unauthorized termination of system daemons or commands issued through launchctl or kill to stop competing services or malware processes. Defenders should monitor unified logs and EDR telemetry for unusual service modifications or terminations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0047](https://attack.mitre.org/detectionstrategies/DET0015#AN0047)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
