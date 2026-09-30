---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0784"
source_url: "https://attack.mitre.org/detectionstrategies/DET0281#AN0784"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0784: Analytic 0784

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0784  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Identifies archive utilities (e.g., ditto, unzip, xar, pkgutil) used to extract payloads to non-standard paths, then correlates with execution or file permission changes (e.g., `chmod +x`) and process spawns from decompressed location.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0784](https://attack.mitre.org/detectionstrategies/DET0281#AN0784)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
