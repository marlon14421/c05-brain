---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1203"
source_url: "https://attack.mitre.org/detectionstrategies/DET0431#AN1203"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1203: Analytic 1203

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1203  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects spoofed emails by analyzing mail server logs (e.g., Postfix, Sendmail) for mismatched header fields, failed SPF/DKIM checks, and anomalies in SMTP proxy logs. Defender observes discrepancies between sending domain, return-path domain, and message metadata.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1203](https://attack.mitre.org/detectionstrategies/DET0431#AN1203)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
