---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1552.002"
stix_relationship_id: "relationship--81cf1179-d422-44fd-9d3d-fadcc8ed2329"
---
# Relationship 3808: G1055 — uses → T1552.002

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.002 - Credentials in Registry|T1552.002: Credentials in Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) had exported credentials from registry hives to include those stored in HKLM.(Citation: Check Point VOID MANTICORE Handala Hack March 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81cf1179-d422-44fd-9d3d-fadcc8ed2329`.
