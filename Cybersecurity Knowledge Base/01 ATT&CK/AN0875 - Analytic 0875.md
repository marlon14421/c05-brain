---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0875"
source_url: "https://attack.mitre.org/detectionstrategies/DET0314#AN0875"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0875: Analytic 0875

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0875  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious execution of network monitoring tools (e.g., Wireshark, tshark, Microsoft Message Analyzer), driver loading indicative of promiscuous mode, or non-admin user privilege escalation to access NICs for capture.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0875](https://attack.mitre.org/detectionstrategies/DET0314#AN0875)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
