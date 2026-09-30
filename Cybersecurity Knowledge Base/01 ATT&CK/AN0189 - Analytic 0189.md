---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0189"
source_url: "https://attack.mitre.org/detectionstrategies/DET0070#AN0189"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0189: Analytic 0189

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0189  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Monitor for malicious payload delivery through phishing where attachments or URLs in email clients (e.g., Thunderbird, mutt) result in unusual file creation or outbound network connections. Focus on correlation between mail logs, file writes, and execution activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0189](https://attack.mitre.org/detectionstrategies/DET0070#AN0189)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
