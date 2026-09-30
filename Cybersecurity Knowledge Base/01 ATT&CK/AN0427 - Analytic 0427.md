---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0427"
source_url: "https://attack.mitre.org/detectionstrategies/DET0149#AN0427"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0427: Analytic 0427

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0427  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects use of unencrypted protocols (e.g., TFTP, FTP, HTTP) to transfer configuration files, routing tables, or logs to untrusted IP addresses, especially using administrative commands like `copy run ftp:`.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0427](https://attack.mitre.org/detectionstrategies/DET0149#AN0427)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
