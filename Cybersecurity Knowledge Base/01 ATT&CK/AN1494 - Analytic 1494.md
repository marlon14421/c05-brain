---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1494"
source_url: "https://attack.mitre.org/detectionstrategies/DET0541#AN1494"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1494: Analytic 1494

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1494  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects adversary behavior where a process enumerates and modifies another process's memory using /proc/[pid]/maps and /proc/[pid]/mem files. This includes identifying gadgets via memory mappings and overwriting process memory via low-level file modification or dd usage.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1494](https://attack.mitre.org/detectionstrategies/DET0541#AN1494)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
