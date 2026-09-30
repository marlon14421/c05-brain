---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0033"
source_url: "https://attack.mitre.org/detectionstrategies/DET0011#AN0033"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0033: Analytic 0033

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0033  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Anomalous traffic from ESXi host management daemons (like hostd or vpxa) embedding non-standard payloads in management protocols (e.g., HTTPS) or beaconing behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0033](https://attack.mitre.org/detectionstrategies/DET0011#AN0033)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
