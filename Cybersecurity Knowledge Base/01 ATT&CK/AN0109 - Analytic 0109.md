---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0109"
source_url: "https://attack.mitre.org/detectionstrategies/DET0039#AN0109"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0109: Analytic 0109

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0109  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlate high-frequency or anomalous DNS query activity with processes that do not normally generate network requests (e.g., Office apps, system utilities). Detect pseudo-random or high-entropy domain lookups indicative of domain generation algorithms (DGAs).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0109](https://attack.mitre.org/detectionstrategies/DET0039#AN0109)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
