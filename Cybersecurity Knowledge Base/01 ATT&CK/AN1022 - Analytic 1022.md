---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1022"
source_url: "https://attack.mitre.org/detectionstrategies/DET0359#AN1022"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1022: Analytic 1022

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1022  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

LaunchAgents or LaunchDaemons initiate persistent Tor or relay processes that make encrypted outbound connections. May be paired with sandbox bypasses or unsigned executables communicating over SOCKS proxies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1022](https://attack.mitre.org/detectionstrategies/DET0359#AN1022)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
