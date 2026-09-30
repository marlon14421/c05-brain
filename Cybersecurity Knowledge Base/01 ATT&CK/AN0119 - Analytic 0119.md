---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0119"
source_url: "https://attack.mitre.org/detectionstrategies/DET0043#AN0119"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0119: Analytic 0119

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0119  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual process or API usage attempting to query system locale, timezone, or keyboard layout (e.g., calls to GetLocaleInfoW, GetTimeZoneInformation). Detection can be enhanced by correlating with processes not typically associated with system configuration queries, such as unknown binaries or scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0119](https://attack.mitre.org/detectionstrategies/DET0043#AN0119)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
