---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1083"
source_url: "https://attack.mitre.org/detectionstrategies/DET0384#AN1083"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1083: Analytic 1083

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1083  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects BusyBox or Ash shell execution from unauthorized logins or remote connections. Focus is on rare shell invocations from DCUI, SSH sessions, or remote management paths. Also watches for payload droppers or persistence artifacts using shell.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1083](https://attack.mitre.org/detectionstrategies/DET0384#AN1083)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
