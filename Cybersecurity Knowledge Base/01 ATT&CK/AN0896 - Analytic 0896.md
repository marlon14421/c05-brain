---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0896"
source_url: "https://attack.mitre.org/detectionstrategies/DET0318#AN0896"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0896: Analytic 0896

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0896  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes like git, curl, or python scripts executing commands that package files (tar, gzip) followed by HTTPS uploads to code repository endpoints. Defender view: detect unusual git push activity or scripted HTTPS requests outside normal developer work hours.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0896](https://attack.mitre.org/detectionstrategies/DET0318#AN0896)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
