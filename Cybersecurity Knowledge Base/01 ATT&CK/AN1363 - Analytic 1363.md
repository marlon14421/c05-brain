---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1363"
source_url: "https://attack.mitre.org/detectionstrategies/DET0495#AN1363"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1363: Analytic 1363

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1363  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Monitor unified logs for access to payment applications, browser plug-ins, or Apple Pay services from non-standard processes. Detect anomalous use of Automator scripts or keychain extraction targeting financial account credentials.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1363](https://attack.mitre.org/detectionstrategies/DET0495#AN1363)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
