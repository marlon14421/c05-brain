---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1641"
source_url: "https://attack.mitre.org/detectionstrategies/DET0597#AN1641"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1641: Analytic 1641

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1641  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of suspicious access to password manager processes (KeePass, 1Password, LastPass, Bitwarden) through abnormal process injection, memory reads, or command-line usage of vault-related DLLs. Correlates process creation with OS API calls and file access to vault databases (.kdbx, .opvault, .ldb).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1641](https://attack.mitre.org/detectionstrategies/DET0597#AN1641)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
