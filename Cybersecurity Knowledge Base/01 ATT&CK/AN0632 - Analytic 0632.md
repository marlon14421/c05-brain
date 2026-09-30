---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0632"
source_url: "https://attack.mitre.org/detectionstrategies/DET0226#AN0632"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0632: Analytic 0632

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0632  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects binaries disguised as media or document types through extension-only masquerading or by modifying the file signature. Observes execution of files whose extension is not typically executable (.jpg, .txt), yet have valid Mach-O headers or execute via Terminal or launch services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0632](https://attack.mitre.org/detectionstrategies/DET0226#AN0632)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
