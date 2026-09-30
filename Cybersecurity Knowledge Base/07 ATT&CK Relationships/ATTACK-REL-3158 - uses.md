---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1135"
target_object: "T1561.002"
stix_relationship_id: "relationship--d8f9ad2e-1548-45b8-9539-4692add2c0fe"
---
# Relationship 3158: S1135 — uses → T1561.002

**Source object:** [[01 ATT&CK/S1135 - MultiLayer Wiper|S1135: MultiLayer Wiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.002 - Disk Structure Wipe|T1561.002: Disk Structure Wipe]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MultiLayer Wiper](https://attack.mitre.org/software/S1135) opens a handle to \\\\\\\\.\\\\PhysicalDrive0 and wipes the first 512 bytes of data from this location, removing the boot sector.(Citation: Unit42 Agrius 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8f9ad2e-1548-45b8-9539-4692add2c0fe`.
