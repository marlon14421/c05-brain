---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1205"
source_url: "https://attack.mitre.org/detectionstrategies/DET0431#AN1205"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1205: Analytic 1205

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1205  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Correlates Office 365 or Google Workspace audit logs for spoofed sender addresses, failed email authentication, and anomalies in message delivery metadata. Defender observes failed SPF/DKIM checks and domain mismatches tied to suspicious campaigns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1205](https://attack.mitre.org/detectionstrategies/DET0431#AN1205)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
