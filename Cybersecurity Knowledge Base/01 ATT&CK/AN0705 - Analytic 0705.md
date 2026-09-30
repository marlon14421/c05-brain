---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0705"
source_url: "https://attack.mitre.org/detectionstrategies/DET0255#AN0705"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0705: Analytic 0705

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0705  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for use of native utilities such as wevtutil.exe or PowerShell cmdlets (Get-WinEvent, Get-EventLog) to enumerate or export logs. Unusual access to security or system event channels, especially by non-administrative users or processes, should be correlated with subsequent file export or network transfer activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0705](https://attack.mitre.org/detectionstrategies/DET0255#AN0705)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
