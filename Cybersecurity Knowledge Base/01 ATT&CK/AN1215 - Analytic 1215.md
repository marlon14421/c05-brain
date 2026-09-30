---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1215"
source_url: "https://attack.mitre.org/detectionstrategies/DET0438#AN1215"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1215: Analytic 1215

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1215  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects custom archiving by monitoring execution of Swift/Objective-C apps or scripts producing high-entropy files with non-standard headers. Correlates unified logs of abnormal NSFileHandle/NSData operations, memory use of XOR/bitwise operations, and file creation events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1215](https://attack.mitre.org/detectionstrategies/DET0438#AN1215)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
