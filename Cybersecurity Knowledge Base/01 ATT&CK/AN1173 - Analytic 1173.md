---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1173"
source_url: "https://attack.mitre.org/detectionstrategies/DET0416#AN1173"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1173: Analytic 1173

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1173  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects internal hosts generating large outbound FTP/TFTP/SMB sessions to external IPs, or file transfers using non-standard ports and application mismatches (e.g., FTP over port 80).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1173](https://attack.mitre.org/detectionstrategies/DET0416#AN1173)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
