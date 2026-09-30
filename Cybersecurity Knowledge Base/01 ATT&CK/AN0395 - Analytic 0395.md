---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0395"
source_url: "https://attack.mitre.org/detectionstrategies/DET0140#AN0395"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0395: Analytic 0395

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0395  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects manual or scripted removal of logs, artifacts, or malware droppings via `rm` or PowerCLI in ESXi shell. Focus on deletions from /tmp/, /var/core/, or /scratch.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0395](https://attack.mitre.org/detectionstrategies/DET0140#AN0395)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
