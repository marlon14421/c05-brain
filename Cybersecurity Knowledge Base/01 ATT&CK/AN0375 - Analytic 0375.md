---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0375"
source_url: "https://attack.mitre.org/detectionstrategies/DET0133#AN0375"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0375: Analytic 0375

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0375  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of the creation of VSCode or JetBrains CLI tunneling profiles followed by persistent remote access via IDE-integrated tunnels, potentially authenticated via GitHub or JetBrains accounts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0375](https://attack.mitre.org/detectionstrategies/DET0133#AN0375)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
