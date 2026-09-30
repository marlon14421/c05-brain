---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0789"
source_url: "https://attack.mitre.org/detectionstrategies/DET0284#AN0789"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0789: Analytic 0789

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0789  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Processes such as osascript, curl, or office applications sending data to text storage APIs/domains. Defender perspective: anomalous clipboard or file reads by unexpected applications immediately followed by outbound HTTPS requests to pastebin-like services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0789](https://attack.mitre.org/detectionstrategies/DET0284#AN0789)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
