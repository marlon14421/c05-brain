---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0055"
source_url: "https://attack.mitre.org/datacomponents/DC0055"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0055: File Access

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0055  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

To events where a file is opened or accessed, making its contents available to the requester. This includes reading, executing, or interacting with files by authorized or unauthorized entities. Examples include logging file access events (e.g., Windows Event ID 4663), monitoring file reads, and detecting unusual file access patterns. Examples: - File Read Operations: A user opens a sensitive document (e.g., financial_report.xlsx) on a shared drive. - File Execution: A script or executable file is accessed and executed (e.g., malware.exe is run from a temporary directory). - Unauthorized File Access: An unauthorized user attempts to access a protected configuration file (e.g., `/etc/passwd` on Linux or `System32` files on Windows). - File Access Patterns: Bulk access to multiple files in a short time (e.g., mass access to documents on a file server). - File Access via Network: Files on a network share are accessed remotely (e.g., logs of SMB file access).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0055](https://attack.mitre.org/datacomponents/DC0055)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
