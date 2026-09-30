---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0058"
source_url: "https://attack.mitre.org/datacomponents/DC0058"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0058: Snapshot Modification

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0058  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Changes made to a cloud snapshot's metadata, attributes, or control settings. These modifications may involve adjusting access permissions, changing retention policies, or altering encryption settings. *Data Collection Measures:* - AWS CloudTrail - Tracks API calls such as `ModifySnapshotAttribute`, `ResetSnapshotAttribute`, and `ModifySnapshotTier`. - Azure Monitor Logs - Logs changes via `Microsoft.Compute/snapshots/write`. - Google Cloud Logging - Captures modifications through `compute.snapshots.setIamPolicy` and `compute.snapshots.patch`.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0058](https://attack.mitre.org/datacomponents/DC0058)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
