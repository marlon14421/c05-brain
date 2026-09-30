---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1037"
source_url: "https://attack.mitre.org/detectionstrategies/DET0368#AN1037"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1037: Analytic 1037

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1037  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects tampered Mac hardware/firmware by analyzing unified logs, EndpointSecurity events, and Apple Mobile File Integrity (AMFI) checks. Behavioral chain: (1) Boot process reports firmware signature mismatch; (2) Secure Boot policy altered; (3) new EFI drivers or hardware devices appear in inventory; (4) system extension loads from unapproved developer IDs post-boot.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1037](https://attack.mitre.org/detectionstrategies/DET0368#AN1037)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
