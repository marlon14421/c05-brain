---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0180"
source_url: "https://attack.mitre.org/detectionstrategies/DET0066#AN0180"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0180: Analytic 0180

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0180  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Behavioral chain: (1) Safari/Chrome/Firefox/Office handles a URL; unified logs show open/click or LSQuarantine assignment, (2) outbound connection to untrusted domain, (3) a new file appears in ~/Downloads or /private/var/folders/* with quarantine flag.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0180](https://attack.mitre.org/detectionstrategies/DET0066#AN0180)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
