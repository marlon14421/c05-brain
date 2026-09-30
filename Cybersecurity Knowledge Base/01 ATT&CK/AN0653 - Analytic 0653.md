---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0653"
source_url: "https://attack.mitre.org/detectionstrategies/DET0235#AN0653"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0653: Analytic 0653

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0653  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Abnormal usage of Preview, ImageMagick, or binary editors to alter images/documents, followed by exfiltration or outbound connections with mismatched file MIME types or payload structure.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0653](https://attack.mitre.org/detectionstrategies/DET0235#AN0653)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
