---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0720"
source_url: "https://attack.mitre.org/detectionstrategies/DET0260#AN0720"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0720: Analytic 0720

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0720  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

On Linux systems, forged credentials may be injected into browser session files, curl/wget headers, or token caches in memory. Detection can leverage auditd to track processes accessing sensitive files (~/.mozilla, ~/.config/chromium, ~/.aws/credentials) and correlate with suspicious outbound connections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0720](https://attack.mitre.org/detectionstrategies/DET0260#AN0720)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
