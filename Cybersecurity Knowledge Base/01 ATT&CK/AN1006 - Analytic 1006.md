---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1006"
source_url: "https://attack.mitre.org/detectionstrategies/DET0354#AN1006"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1006: Analytic 1006

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1006  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Unexpected inbound or outbound VNC/SSH/Screen Sharing connections from external sources → repeated failed logins followed by success → remote interactive sessions or abnormal file transfers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1006](https://attack.mitre.org/detectionstrategies/DET0354#AN1006)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
