---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0008"
source_url: "https://attack.mitre.org/detectionstrategies/DET0003#AN0008"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0008: Analytic 0008

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0008  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

macOS clients joined to AD via LDAP may script account provisioning via `dsconfigad`, `dscl`, or LDAP scripts. Detection occurs when such tools run on a domain-joined system, followed by authentication attempts by a previously unseen account.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0008](https://attack.mitre.org/detectionstrategies/DET0003#AN0008)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
