---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1361"
source_url: "https://attack.mitre.org/detectionstrategies/DET0495#AN1361"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1361: Analytic 1361

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1361  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for anomalous access to financial applications, browser-based banking sessions, or enterprise ERP systems from Windows endpoints. Detect mass emailing of payment instructions, sudden rule changes in Outlook for financial staff, or use of clipboard data exfiltration tied to cryptocurrency wallet addresses.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1361](https://attack.mitre.org/detectionstrategies/DET0495#AN1361)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
