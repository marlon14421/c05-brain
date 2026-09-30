---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1054"
source_url: "https://attack.mitre.org/detectionstrategies/DET0374#AN1054"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1054: Analytic 1054

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1054  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Monitor for creation of new Power Automate flows or equivalent automation scripts that trigger on user or file events. Detect anomalous actions performed by these automations, such as email forwarding, anonymous link creation, or unexpected API calls to external endpoints.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1054](https://attack.mitre.org/detectionstrategies/DET0374#AN1054)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
