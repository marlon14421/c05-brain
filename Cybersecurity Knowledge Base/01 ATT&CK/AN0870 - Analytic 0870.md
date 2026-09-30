---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0870"
source_url: "https://attack.mitre.org/detectionstrategies/DET0311#AN0870"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0870: Analytic 0870

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0870  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection of fake or spoofed macOS Security & Privacy GUIs showing healthy status after XProtect, Gatekeeper, or AV processes are disabled. Correlates user-space UI process creation with terminated or missing security daemons.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0870](https://attack.mitre.org/detectionstrategies/DET0311#AN0870)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
