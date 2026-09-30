---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0379"
source_url: "https://attack.mitre.org/detectionstrategies/DET0135#AN0379"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0379: Analytic 0379

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0379  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects unauthorized use of SMTP/IMAP/POP3 by suspicious binaries (e.g., PowerShell, rundll32) to exfiltrate data or beacon via email, often bypassing proxy or content filters.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0379](https://attack.mitre.org/detectionstrategies/DET0135#AN0379)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
