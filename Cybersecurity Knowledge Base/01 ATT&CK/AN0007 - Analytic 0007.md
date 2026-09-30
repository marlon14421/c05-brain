---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0007"
source_url: "https://attack.mitre.org/detectionstrategies/DET0003#AN0007"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0007: Analytic 0007

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0007  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Adversary with access to domain management tools (e.g., `realmd`, `samba-tool`, `ldapmodify`) creates a new domain user via command-line utilities. Behavior chain: LDAP command or script triggers → user entry added in AD via Kerberos/LDAP traffic.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0007](https://attack.mitre.org/detectionstrategies/DET0003#AN0007)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
