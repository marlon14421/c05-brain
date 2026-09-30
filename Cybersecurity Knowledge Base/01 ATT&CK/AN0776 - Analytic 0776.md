---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0776"
source_url: "https://attack.mitre.org/detectionstrategies/DET0278#AN0776"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0776: Analytic 0776

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0776  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Abnormal modification of EFI firmware binaries in /System/Library/CoreServices/ or NVRAM parameters not associated with OS updates. Unified logs capturing calls to bless or nvram commands executed from untrusted parent processes. Sudden unsigned kext loads after EFI variable tampering.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0776](https://attack.mitre.org/detectionstrategies/DET0278#AN0776)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
