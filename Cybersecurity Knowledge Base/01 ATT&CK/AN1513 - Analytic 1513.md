---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1513"
source_url: "https://attack.mitre.org/detectionstrategies/DET0548#AN1513"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1513: Analytic 1513

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1513  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Office apps or scripts writing files followed by xattr manipulation (to evade quarantine) and subsequent HTTPS uploads. Defender perspective: anomalous file modification + outbound TLS traffic originating from non-networking apps (Word, Excel, Preview).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1513](https://attack.mitre.org/detectionstrategies/DET0548#AN1513)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
