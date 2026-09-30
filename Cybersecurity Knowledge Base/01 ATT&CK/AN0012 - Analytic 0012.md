---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0012"
source_url: "https://attack.mitre.org/detectionstrategies/DET0005#AN0012"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0012: Analytic 0012

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0012  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of binaries where the on-disk filename does not match PE metadata such as OriginalFilename or InternalName. Often observed with renamed LOLBAS or system binaries like rundll32, powershell, or psexec.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0012](https://attack.mitre.org/detectionstrategies/DET0005#AN0012)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
