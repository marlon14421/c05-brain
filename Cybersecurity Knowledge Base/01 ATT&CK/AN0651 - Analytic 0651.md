---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0651"
source_url: "https://attack.mitre.org/detectionstrategies/DET0235#AN0651"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0651: Analytic 0651

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0651  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detect the creation or modification of common media file formats (e.g., .jpg, .png, .wav) following suspicious process activity like compression or encryption, especially when paired with lateral movement or exfiltration behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0651](https://attack.mitre.org/detectionstrategies/DET0235#AN0651)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
