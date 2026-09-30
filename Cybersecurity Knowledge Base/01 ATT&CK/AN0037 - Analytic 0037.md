---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0037"
source_url: "https://attack.mitre.org/detectionstrategies/DET0013#AN0037"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0037: Analytic 0037

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0037  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Access to browser artifact locations (e.g., Chrome, Edge, Firefox) by processes like PowerShell, cmd.exe, or unknown tools, followed by file reads, decoding, or export operations indicating enumeration of bookmarks, autofill, or history databases.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0037](https://attack.mitre.org/detectionstrategies/DET0013#AN0037)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
