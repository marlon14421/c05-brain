---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1445"
source_url: "https://attack.mitre.org/detectionstrategies/DET0522#AN1445"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1445: Analytic 1445

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1445  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects attempts to forge or replay Kerberos tickets by monitoring Unified Logs for anomalous kinit/klist activity and correlating unusual authentication sequences.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1445](https://attack.mitre.org/detectionstrategies/DET0522#AN1445)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
