---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1384"
source_url: "https://attack.mitre.org/detectionstrategies/DET0502#AN1384"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1384: Analytic 1384

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1384  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Abuse of file/registry attributes to hide malicious files, directories, or services. Defender view: detection of attrib.exe setting hidden/system flags, creation of Alternate Data Streams, or registry keys altering file visibility.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1384](https://attack.mitre.org/detectionstrategies/DET0502#AN1384)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
