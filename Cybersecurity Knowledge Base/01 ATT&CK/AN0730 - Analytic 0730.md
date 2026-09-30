---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0730"
source_url: "https://attack.mitre.org/detectionstrategies/DET0262#AN0730"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0730: Analytic 0730

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0730  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Use unified logs to detect unusual DNS responses correlated with subsequent connections to calculated or non-standard ports. Monitor non-browser apps making repeated outbound connections that deviate from expected patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0730](https://attack.mitre.org/detectionstrategies/DET0262#AN0730)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
