---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1089"
target_object: "T1071.002"
stix_relationship_id: "relationship--942ced7d-f5a7-4c8d-ba66-e28479f7447a"
---
# Relationship 3886: S1089 — uses → T1071.002

**Source object:** [[01 ATT&CK/S1089 - SharpDisco|S1089: SharpDisco]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.002 - File Transfer Protocols|T1071.002: File Transfer Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SharpDisco](https://attack.mitre.org/software/S1089) has the ability to transfer data between SMB shares.(Citation: MoustachedBouncer ESET August 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--942ced7d-f5a7-4c8d-ba66-e28479f7447a`.
