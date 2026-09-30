---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1213"
source_url: "https://attack.mitre.org/detectionstrategies/DET0438#AN1213"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1213: Analytic 1213

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1213  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious custom compression/encryption routines through anomalous script or binary execution that produces high-entropy files without standard archiving utilities. Correlates script execution, memory API usage (bitwise ops, CryptoAPI calls), and creation of archive-like files with uncommon headers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1213](https://attack.mitre.org/detectionstrategies/DET0438#AN1213)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
