---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1178"
source_url: "https://attack.mitre.org/detectionstrategies/DET0419#AN1178"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1178: Analytic 1178

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1178  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlate DNS queries that generate domains with high entropy or gibberish patterns, combined with short-lived connections from unusual processes. Monitor Sysmon DNS events and Windows Security logs for abnormal query rates and failed lookups.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1178](https://attack.mitre.org/detectionstrategies/DET0419#AN1178)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
