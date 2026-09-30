---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0116"
source_url: "https://attack.mitre.org/detectionstrategies/DET0040#AN0116"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0116: Analytic 0116

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0116  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects adversary removal of persistence implants (e.g., rc.local entries or crontab injections) via CLI (`rm`, `sed`, `crontab -r`) and deletion of startup or management scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0116](https://attack.mitre.org/detectionstrategies/DET0040#AN0116)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
