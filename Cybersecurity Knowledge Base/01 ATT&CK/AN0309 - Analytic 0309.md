---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0309"
source_url: "https://attack.mitre.org/detectionstrategies/DET0111#AN0309"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0309: Analytic 0309

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0309  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detection correlates message events in email and collaboration tools (e.g., Outlook, Teams) that contain regex-like patterns resembling credentials, API keys, or tokens. Anomalous forwarding or bulk copy activity of chat/email content containing secrets is flagged. Suspicious behavior includes users pasting secrets into direct messages or attaching config files with passwords.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0309](https://attack.mitre.org/detectionstrategies/DET0111#AN0309)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
