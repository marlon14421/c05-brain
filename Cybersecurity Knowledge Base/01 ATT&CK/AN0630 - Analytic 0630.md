---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0630"
source_url: "https://attack.mitre.org/detectionstrategies/DET0226#AN0630"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0630: Analytic 0630

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0630  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects behavior where files with non-executable or misleading extensions (e.g., .jpg, .txt) are created or modified but subsequently executed as binaries based on internal file headers or abnormal parent process lineage. This includes identifying polyglot files or malformed magic bytes indicative of masquerading attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0630](https://attack.mitre.org/detectionstrategies/DET0226#AN0630)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
