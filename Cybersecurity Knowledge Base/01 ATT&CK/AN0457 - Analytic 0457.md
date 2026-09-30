---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0457"
source_url: "https://attack.mitre.org/detectionstrategies/DET0161#AN0457"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0457: Analytic 0457

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0457  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Chain: (1) execution of `pwpolicy` or MDM/DirectoryService reads of account policies; (2) optional read of `/Library/Preferences/com.apple.loginwindow` or config profiles; (3) follow-on credential probing or lateral movement by same user/session. Use unified logs and process telemetry.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0457](https://attack.mitre.org/detectionstrategies/DET0161#AN0457)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
