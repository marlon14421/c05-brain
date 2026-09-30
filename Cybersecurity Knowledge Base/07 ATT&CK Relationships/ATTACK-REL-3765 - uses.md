---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1050"
target_object: "T1112"
stix_relationship_id: "relationship--d45fe5a0-f9e5-4f05-b40b-8693c8eab0f7"
---
# Relationship 3765: S1050 — uses → T1112

**Source object:** [[01 ATT&CK/S1050 - PcShare|S1050: PcShare]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PcShare](https://attack.mitre.org/software/S1050) can delete its persistence mechanisms from the registry.(Citation: Bitdefender FunnyDream Campaign November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d45fe5a0-f9e5-4f05-b40b-8693c8eab0f7`.
