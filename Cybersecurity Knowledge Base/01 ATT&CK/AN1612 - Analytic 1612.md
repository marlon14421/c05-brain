---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1612"
source_url: "https://attack.mitre.org/detectionstrategies/DET0587#AN1612"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1612: Analytic 1612

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1612  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of processes performing local or domain account enumeration by invoking account directory queries or security APIs followed by structured output of account lists. The defender observes command execution or API invocation patterns that retrieve account information and produce enumeration artifacts shortly afterward.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1612](https://attack.mitre.org/detectionstrategies/DET0587#AN1612)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
