---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0719"
source_url: "https://attack.mitre.org/detectionstrategies/DET0260#AN0719"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0719: Analytic 0719

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0719  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Forged web credentials on Windows endpoints may be detected by anomalous browser cookie files, local token cache manipulations, or tools injecting tokens into sessions. Defenders may observe processes accessing LSASS or browser credential stores unexpectedly, followed by unusual logon sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0719](https://attack.mitre.org/detectionstrategies/DET0260#AN0719)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
