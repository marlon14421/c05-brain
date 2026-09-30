---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1248"
source_url: "https://attack.mitre.org/detectionstrategies/DET0452#AN1248"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1248: Analytic 1248

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1248  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection monitors modification of code signing attributes, Gatekeeper/quarantine flags, and insertion of new trust certificates via security add-trusted-cert. Identifies adversary use of xattr to strip quarantine flags from downloaded binaries. Correlates with abnormal module loads bypassing SIP protections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1248](https://attack.mitre.org/detectionstrategies/DET0452#AN1248)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
