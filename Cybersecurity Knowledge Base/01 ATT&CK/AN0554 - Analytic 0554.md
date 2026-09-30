---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0554"
source_url: "https://attack.mitre.org/detectionstrategies/DET0192#AN0554"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0554: Analytic 0554

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0554  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Suspicious rule creation within Outlook or Exchange clients, including auto-move or delete conditions tied to incident or security alert keywords. Defender perspective: correlation between missing inbound emails and newly added mailbox rules.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0554](https://attack.mitre.org/detectionstrategies/DET0192#AN0554)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
