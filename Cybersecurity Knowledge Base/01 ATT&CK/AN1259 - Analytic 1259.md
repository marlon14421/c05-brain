---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1259"
source_url: "https://attack.mitre.org/detectionstrategies/DET0458#AN1259"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1259: Analytic 1259

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1259  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary modifies Active Directory domain trust settings via `netdom`, `nltest`, or PowerShell to add new domain trust or alter federation. Modifications occur in AD object attributes like trustDirection, trustType, trustAttributes, often paired with SeEnableDelegationPrivilege or certificate injection.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1259](https://attack.mitre.org/detectionstrategies/DET0458#AN1259)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
