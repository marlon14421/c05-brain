---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0188"
source_url: "https://attack.mitre.org/detectionstrategies/DET0070#AN0188"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0188: Analytic 0188

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0188  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual inbound email activity where attachments or embedded URLs are delivered to users followed by execution of new processes or suspicious document behavior. Detection involves correlating email metadata, file creation, and network activity after a phishing message is received.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0188](https://attack.mitre.org/detectionstrategies/DET0070#AN0188)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
