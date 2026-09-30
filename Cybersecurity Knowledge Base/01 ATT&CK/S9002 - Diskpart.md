---
type: "Tool"
source: MITRE ATT&CK
id: "S9002"
source_url: "https://attack.mitre.org/software/S9002"
created: "2026-01-26"
modified: "2026-04-23"
---
# S9002: Diskpart

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tool  
**ATT&CK ID:** S9002  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Diskpart](https://attack.mitre.org/software/S9002) is a Windows command-line utility that is used to manage the computer’s drives, which includes disks, partitions, volumes and virtual hard disks.(Citation: Microsoft_diskpart_Feb2023) Adversaries may abuse [Diskpart](https://attack.mitre.org/software/S9002) to perform discovery and destructive actions on a system’s storage. For example, adversaries have been observed using [Diskpart](https://attack.mitre.org/software/S9002) to conduct [Discovery](https://attack.mitre.org/tactics/TA0007) techniques to enumerate disks and volumes to gather information about the host environment, and to execute commands such as `clean all` to remove partition information and overwrite data across disks, resulting in data destruction.(Citation: Trendmicro_RansomHub_Dec2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9002](https://attack.mitre.org/software/S9002)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
