---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1208"
source_url: "https://attack.mitre.org/detectionstrategies/DET0434#AN1208"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1208: Analytic 1208

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1208  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects creation or modification of user-level Launch Agents in monitored directories using `.plist` files with suspicious `ProgramArguments` or `RunAtLoad` keys. Correlates file write activity with execution of `launchctl` or unsigned binaries invoked at login.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1208](https://attack.mitre.org/detectionstrategies/DET0434#AN1208)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
