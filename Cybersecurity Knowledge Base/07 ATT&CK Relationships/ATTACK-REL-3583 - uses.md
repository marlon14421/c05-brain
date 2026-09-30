---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1199"
target_object: "T1070.004"
stix_relationship_id: "relationship--be7d0718-28e5-4f49-9636-c5deafa63530"
---
# Relationship 3583: S1199 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1199 - LockBit 2.0|S1199: LockBit 2.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LockBit 2.0](https://attack.mitre.org/software/S1199) can delete itself from disk after execution.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Palo Alto Lockbit 2.0 JUN 2022)(Citation: Cybereason Lockbit 2.0)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be7d0718-28e5-4f49-9636-c5deafa63530`.
