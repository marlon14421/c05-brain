---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0721"
source_url: "https://attack.mitre.org/detectionstrategies/DET0260#AN0721"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0721: Analytic 0721

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0721  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Forged credentials on macOS may be visible through Unified Logs showing abnormal access to Keychain or browser session files. Correlated with anomalous web session usage from Safari or Chrome processes outside typical user context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0721](https://attack.mitre.org/detectionstrategies/DET0260#AN0721)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
