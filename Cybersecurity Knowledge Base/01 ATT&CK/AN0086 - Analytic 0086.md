---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0086"
source_url: "https://attack.mitre.org/detectionstrategies/DET0029#AN0086"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0086: Analytic 0086

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0086  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Outlook form execution upon message receipt or client launch results in automated code execution within user session. Form definitions deviate from standard templates and include script logic or COM object calls embedded in form fields.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0086](https://attack.mitre.org/detectionstrategies/DET0029#AN0086)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
