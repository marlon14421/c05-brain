---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1321"
source_url: "https://attack.mitre.org/detectionstrategies/DET0480#AN1321"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1321: Analytic 1321

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1321  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects tampering of IIS-based login pages (e.g., default.aspx, login.aspx) tied to VPN, OWA, or SharePoint via script injection or unexpected editor processes modifying web roots.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1321](https://attack.mitre.org/detectionstrategies/DET0480#AN1321)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
