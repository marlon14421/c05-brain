---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0218"
source_url: "https://attack.mitre.org/detectionstrategies/DET0079#AN0218"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0218: Analytic 0218

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0218  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection of hijacked VNC or SSH sessions on macOS where adversaries take over an existing session rather than authenticating directly. Indicators include process execution from active sessions without new logon events, manipulation of TTY sessions, or anomalous network activity tied to dormant sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0218](https://attack.mitre.org/detectionstrategies/DET0079#AN0218)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
