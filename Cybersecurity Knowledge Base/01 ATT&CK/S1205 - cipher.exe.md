---
type: "Tool"
source: MITRE ATT&CK
id: "S1205"
source_url: "https://attack.mitre.org/software/S1205"
created: "2025-02-25"
modified: "2025-03-10"
---
# S1205: cipher.exe

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tool  
**ATT&CK ID:** S1205  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[cipher.exe](https://attack.mitre.org/software/S1205) is a native Microsoft utility that manages encryption of directories and files on NTFS (New Technology File System) partitions by using the Encrypting File System (EFS).(Citation: cipher.exe)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1205](https://attack.mitre.org/software/S1205)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
