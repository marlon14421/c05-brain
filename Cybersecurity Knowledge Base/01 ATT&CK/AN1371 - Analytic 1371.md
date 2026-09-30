---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1371"
source_url: "https://attack.mitre.org/detectionstrategies/DET0497#AN1371"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1371: Analytic 1371

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1371  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection of adversary disabling endpoint security tools by unloading launch agents/daemons, modifying configuration profiles, or disabling Gatekeeper/XProtect/logging settings, or removing endpoint agents followed by telemetry loss.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1371](https://attack.mitre.org/detectionstrategies/DET0497#AN1371)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
