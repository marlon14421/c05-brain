---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0322"
source_url: "https://attack.mitre.org/detectionstrategies/DET0115#AN0322"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0322: Analytic 0322

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0322  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Phishing attempts via iCloud Mail, Gmail, or social media apps accessed on macOS systems. Defender view includes Mail.app or Safari downloads of files followed by osascript, Terminal, or abnormal child process execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0322](https://attack.mitre.org/detectionstrategies/DET0115#AN0322)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
