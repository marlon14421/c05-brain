---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0162"
source_url: "https://attack.mitre.org/detectionstrategies/DET0059#AN0162"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0162: Analytic 0162

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0162  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlate unauthorized or anomalous file modifications, deletions, or metadata changes with suspicious process execution or API calls. Detect abnormal changes to structured data (e.g., database files, logs, financial records) outside expected business process activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0162](https://attack.mitre.org/detectionstrategies/DET0059#AN0162)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
