---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1460"
source_url: "https://attack.mitre.org/detectionstrategies/DET0526#AN1460"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1460: Analytic 1460

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1460  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects use of macOS-native archiving or encryption tools (zip, ditto, hdiutil) for staging collected data. Identifies unexpected invocation of archive utilities by Office apps, browsers, or background daemons. Correlates file creation of .zip/.dmg containers with process lineage anomalies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1460](https://attack.mitre.org/detectionstrategies/DET0526#AN1460)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
