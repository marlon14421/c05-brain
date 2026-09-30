---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1603"
source_url: "https://attack.mitre.org/detectionstrategies/DET0582#AN1603"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1603: Analytic 1603

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1603  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detection of unauthorized changes to boot configurations pointing to TFTP servers, unusual firmware loads during netbooting, or suspicious TFTP traffic. Correlation of boot config modifications, command history logs, and unexpected system image hashes provides detection coverage for adversaries attempting to persist via malicious TFTP boot images.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1603](https://attack.mitre.org/detectionstrategies/DET0582#AN1603)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
