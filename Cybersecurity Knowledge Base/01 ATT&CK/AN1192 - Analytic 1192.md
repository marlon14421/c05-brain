---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1192"
source_url: "https://attack.mitre.org/detectionstrategies/DET0425#AN1192"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1192: Analytic 1192

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1192  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects guest VMs or management agents issuing HTTP(S) traffic to external services without a valid patch management or backup justification.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1192](https://attack.mitre.org/detectionstrategies/DET0425#AN1192)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
