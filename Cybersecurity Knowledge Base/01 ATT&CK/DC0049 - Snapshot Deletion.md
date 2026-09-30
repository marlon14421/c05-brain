---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0049"
source_url: "https://attack.mitre.org/datacomponents/DC0049"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0049: Snapshot Deletion

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0049  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The removal of a point-in-time backup of a cloud storage volume, virtual machine (VM), or database. *Data Collection Measures:* - AWS CloudTrail - Logs `DeleteSnapshot` API calls in EC2, RDS, and EBS services. - Azure Monitor Logs - Tracks snapshot deletions via `Microsoft.Compute/snapshots/delete` API calls. - Google Cloud Logging - Detects snapshot removal through `compute.disks.deleteSnapshot` events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0049](https://attack.mitre.org/datacomponents/DC0049)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
