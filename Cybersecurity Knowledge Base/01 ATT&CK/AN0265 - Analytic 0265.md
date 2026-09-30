---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0265"
source_url: "https://attack.mitre.org/detectionstrategies/DET0096#AN0265"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0265: Analytic 0265

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0265  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Account attribute changes (e.g., password set, group membership, servicePrincipalName, logon hours) correlated with unusual process lineage or timing, indicating privilege escalation or persistence via valid accounts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0265](https://attack.mitre.org/detectionstrategies/DET0096#AN0265)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
