---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0229"
source_url: "https://attack.mitre.org/detectionstrategies/DET0082#AN0229"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0229: Analytic 0229

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0229  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary modifies internal UI messages (e.g., login banners, desktop wallpapers) or hosted intranet web pages by creating or altering content files using scripts or unauthorized access. Often preceded by privilege escalation or web shell deployment.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0229](https://attack.mitre.org/detectionstrategies/DET0082#AN0229)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
