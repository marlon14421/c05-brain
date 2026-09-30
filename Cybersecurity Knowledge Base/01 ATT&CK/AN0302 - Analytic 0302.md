---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0302"
source_url: "https://attack.mitre.org/detectionstrategies/DET0108#AN0302"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0302: Analytic 0302

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0302  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Atypical processes (e.g., powershell.exe, regsvr32.exe) encode large outbound traffic using Base64 or other character encodings; this traffic is sent over uncommon ports or embedded in protocol fields (e.g., HTTP cookies or headers).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0302](https://attack.mitre.org/detectionstrategies/DET0108#AN0302)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
