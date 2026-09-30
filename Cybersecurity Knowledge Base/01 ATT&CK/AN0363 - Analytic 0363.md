---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0363"
source_url: "https://attack.mitre.org/detectionstrategies/DET0129#AN0363"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0363: Analytic 0363

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0363  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary enumeration of domain accounts using net.exe, PowerShell, WMI, or LDAP queries from non-domain controllers or non-admin endpoints.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0363](https://attack.mitre.org/detectionstrategies/DET0129#AN0363)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
