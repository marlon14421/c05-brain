---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0792"
source_url: "https://attack.mitre.org/detectionstrategies/DET0286#AN0792"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0792: Analytic 0792

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0792  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for anomalous email activity originating from Windows-hosted applications (e.g., Outlook) where the sending account name or display name does not match the underlying SMTP address. Detect abnormal volume of outbound messages containing sensitive keywords (e.g., 'payment', 'wire transfer') or anomalous login locations for accounts associated with email sending activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0792](https://attack.mitre.org/detectionstrategies/DET0286#AN0792)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
