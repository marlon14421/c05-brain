---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1635"
source_url: "https://attack.mitre.org/detectionstrategies/DET0595#AN1635"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1635: Analytic 1635

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1635  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects exploitation of macOS security and integrity services, such as Gatekeeper, XProtect, or EDR agents. Defender observations include unsigned processes attempting privileged operations, abnormal termination of security daemons, or modification of system integrity logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1635](https://attack.mitre.org/detectionstrategies/DET0595#AN1635)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
