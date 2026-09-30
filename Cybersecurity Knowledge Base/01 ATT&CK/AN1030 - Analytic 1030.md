---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1030"
source_url: "https://attack.mitre.org/detectionstrategies/DET0363#AN1030"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1030: Analytic 1030

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1030  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

A non-privileged or abnormal process attempts to open a handle with full access (0x1F0FFF) to lsass.exe and subsequently invokes memory dump, file creation, or registry modification indicative of credential scraping. This behavior chain reflects staged credential theft activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1030](https://attack.mitre.org/detectionstrategies/DET0363#AN1030)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
