---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0531"
source_url: "https://attack.mitre.org/detectionstrategies/DET0186#AN0531"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0531: Analytic 0531

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0531  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Automated execution of native utilities and scripts to discover, enumerate, and exfiltrate files and clipboard content. Focus is on detecting repeated file access, scripting engine use, and use of command-line utilities commonly leveraged by collection scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0531](https://attack.mitre.org/detectionstrategies/DET0186#AN0531)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
