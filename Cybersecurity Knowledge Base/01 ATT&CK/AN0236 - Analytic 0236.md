---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0236"
source_url: "https://attack.mitre.org/detectionstrategies/DET0086#AN0236"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0236: Analytic 0236

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0236  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for creation of WMI EventFilter, EventConsumer, and FilterToConsumerBinding objects through WMI or MOF file execution. Detect command-line execution of `mofcomp.exe`, usage of `Register-WmiEvent` via PowerShell, and anomalous child processes of `WmiPrvSE.exe` that indicate triggered execution. Look for lateral anomalies in process lineage and WMI logging channels.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0236](https://attack.mitre.org/detectionstrategies/DET0086#AN0236)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
