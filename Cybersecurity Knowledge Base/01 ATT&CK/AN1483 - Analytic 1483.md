---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1483"
source_url: "https://attack.mitre.org/detectionstrategies/DET0538#AN1483"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1483: Analytic 1483

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1483  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes such as plink.exe, ssh.exe, or netsh.exe establishing outbound network connections where traffic patterns show encapsulated protocols (e.g., RDP over SSH). Defender observations include anomalous process-to-network relationships, large asymmetric data flows, and port usage mismatches.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1483](https://attack.mitre.org/detectionstrategies/DET0538#AN1483)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
