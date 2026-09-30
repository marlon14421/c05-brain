---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0657"
source_url: "https://attack.mitre.org/detectionstrategies/DET0236#AN0657"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0657: Analytic 0657

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0657  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Phishing attachment detection on macOS through correlation of Mail app logs, file creation in user directories, and abnormal process execution (e.g., Preview.app or Mail.app spawning Terminal or scripting binaries). Network traffic after attachment interaction is also monitored.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0657](https://attack.mitre.org/detectionstrategies/DET0236#AN0657)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
