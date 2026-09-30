---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0399"
source_url: "https://attack.mitre.org/detectionstrategies/DET0142#AN0399"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0399: Analytic 0399

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0399  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects unauthorized or anomalous use of command-line interfaces (CLI) on network devices. Focuses on remote access sessions (e.g., SSH/Telnet), privilege escalation within CLI sessions, execution of high-risk commands (e.g., config replace, terminal monitor, no logging), and configuration changes outside of approved windows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0399](https://attack.mitre.org/detectionstrategies/DET0142#AN0399)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
