---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1004"
source_url: "https://attack.mitre.org/detectionstrategies/DET0354#AN1004"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1004: Analytic 1004

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1004  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual or unauthorized external remote access attempts (e.g., RDP, VPN, Citrix) → repeated failed logins followed by a successful session from uncommon geolocations or outside business hours → subsequent internal lateral movement or data exfiltration activities.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1004](https://attack.mitre.org/detectionstrategies/DET0354#AN1004)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
