---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1245"
source_url: "https://attack.mitre.org/detectionstrategies/DET0451#AN1245"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1245: Analytic 1245

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1245  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Defenders can identify PowerShell profile-based persistence by correlating file creation or modification in known profile locations with subsequent PowerShell process launches that do not use the `-NoProfile` flag. Profile scripts loading unusual modules or launching external programs, particularly under elevated contexts, are suspicious and may represent adversary persistence or privilege escalation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1245](https://attack.mitre.org/detectionstrategies/DET0451#AN1245)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
