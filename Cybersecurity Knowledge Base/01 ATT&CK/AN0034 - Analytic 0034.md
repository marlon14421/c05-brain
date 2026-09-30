---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0034"
source_url: "https://attack.mitre.org/detectionstrategies/DET0012#AN0034"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0034: Analytic 0034

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0034  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Discrepancies between VBA source code and p-code inside Office documents. Defender perspective: anomalies in file metadata streams, execution of Office processes loading macros without source code consistency, and script execution with no corresponding source metadata.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0034](https://attack.mitre.org/detectionstrategies/DET0012#AN0034)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
