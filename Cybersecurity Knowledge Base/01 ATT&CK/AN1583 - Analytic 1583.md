---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1583"
source_url: "https://attack.mitre.org/detectionstrategies/DET0574#AN1583"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1583: Analytic 1583

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1583  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of network enumeration utilities (e.g., net.exe, ping.exe, tracert.exe) in short succession, often chained with lateral movement tools or system enumeration commands.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1583](https://attack.mitre.org/detectionstrategies/DET0574#AN1583)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
