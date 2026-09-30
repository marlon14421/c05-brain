---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0016"
source_url: "https://attack.mitre.org/detectionstrategies/DET0007#AN0016"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0016: Analytic 0016

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0016  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary uses nltest, PowerShell, or Win32/.NET API to enumerate domain trust relationships (via DSEnumerateDomainTrusts, GetAllTrustRelationships, or LDAP queries), followed by discovery or authentication staging.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0016](https://attack.mitre.org/detectionstrategies/DET0007#AN0016)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
