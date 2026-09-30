---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0047"
source_url: "https://attack.mitre.org/datacomponents/DC0047"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0047: Snapshot Enumeration

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0047  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The process of listing or retrieving metadata about existing snapshots in a cloud environment. *Data Collection Measures:* - AWS CloudTrail - Logs API calls such as `DescribeSnapshots`, `ListSnapshots`, and `GetSnapshotAttributes`. - Azure Monitor Logs - Tracks snapshot enumeration via `Microsoft.Compute/snapshots/read`. - Google Cloud Logging - Detects snapshot listing through `compute.disks.listSnapshots`.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0047](https://attack.mitre.org/datacomponents/DC0047)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
