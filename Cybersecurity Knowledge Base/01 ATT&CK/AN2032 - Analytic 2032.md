---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2032"
source_url: "https://attack.mitre.org/detectionstrategies/DET0898#AN2032"
created: "2025-10-23"
modified: "2025-10-24"
---
# AN2032: Analytic 2032

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2032  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Observation of scripted network requests (e.g., using osascript, curl, or python) that include mismatched or spoofed browser User-Agent strings compared to the typical macOS Safari or Chrome baseline, especially when triggered by non-interactive launch agents, login hooks, or background daemons.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2032](https://attack.mitre.org/detectionstrategies/DET0898#AN2032)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
