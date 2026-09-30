---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0449"
source_url: "https://attack.mitre.org/detectionstrategies/DET0160#AN0449"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0449: Analytic 0449

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0449  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Monitor for excessive or anomalous MFA push notifications or token requests, especially when login attempts originate from unusual IPs or geolocations and do not correspond to legitimate user-initiated sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0449](https://attack.mitre.org/detectionstrategies/DET0160#AN0449)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
