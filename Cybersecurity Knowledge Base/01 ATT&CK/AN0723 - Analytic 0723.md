---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0723"
source_url: "https://attack.mitre.org/detectionstrategies/DET0260#AN0723"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0723: Analytic 0723

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0723  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Forged web credentials in Office Suite contexts may appear as abnormal authentication headers in Outlook or Teams traffic, or unexplained OAuth grants in M365/Azure logs. Defenders should correlate token usage events with missing authentication flows and mismatched device/user context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0723](https://attack.mitre.org/detectionstrategies/DET0260#AN0723)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
