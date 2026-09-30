---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0179"
source_url: "https://attack.mitre.org/detectionstrategies/DET0066#AN0179"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0179: Analytic 0179

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0179  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Behavioral chain: (1) browser/office/GUI mail client opens a URL, (2) outbound connection to untrusted domain, (3) a new file is saved in $HOME/Downloads, /tmp, or cache immediately after.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0179](https://attack.mitre.org/detectionstrategies/DET0066#AN0179)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
