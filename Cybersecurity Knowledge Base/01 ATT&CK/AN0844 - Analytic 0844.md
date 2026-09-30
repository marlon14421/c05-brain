---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0844"
source_url: "https://attack.mitre.org/detectionstrategies/DET0302#AN0844"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0844: Analytic 0844

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0844  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

A source performs a closed-port sequence; the endpoint enables a PF/socketfilterfw rule or a background process binds a port; then a successful connection completes from the same source.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0844](https://attack.mitre.org/detectionstrategies/DET0302#AN0844)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
