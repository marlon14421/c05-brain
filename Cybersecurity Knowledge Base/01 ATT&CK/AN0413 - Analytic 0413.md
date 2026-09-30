---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0413"
source_url: "https://attack.mitre.org/detectionstrategies/DET0146#AN0413"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0413: Analytic 0413

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0413  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Destruction via `rm -rf`, overwrite with `dd` or `srm`, often executed by script in /tmp or /private/tmp, may also involve file overwrite to political or decoy image data.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0413](https://attack.mitre.org/detectionstrategies/DET0146#AN0413)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
