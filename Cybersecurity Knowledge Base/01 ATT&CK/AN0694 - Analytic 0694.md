---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0694"
source_url: "https://attack.mitre.org/detectionstrategies/DET0250#AN0694"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0694: Analytic 0694

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0694  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Defenders observe command-line executions or API-based registry reads targeting sensitive paths like HKLM or HKCU with keyword filters such as 'password', 'cred', or 'logon'. Typically performed by Reg.exe, PowerShell, custom binaries, or offensive tools such as Cobalt Strike. Correlation with process ancestry and command-line arguments indicates suspicious credential discovery activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0694](https://attack.mitre.org/detectionstrategies/DET0250#AN0694)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
