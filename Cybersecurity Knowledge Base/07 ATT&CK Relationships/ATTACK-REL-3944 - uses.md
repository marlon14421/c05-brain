---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1213.006"
stix_relationship_id: "relationship--d0d35cd6-3fdb-476e-b830-214f32c2d104"
---
# Relationship 3944: G1057 — uses → T1213.006

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1213.006 - Databases|T1213.006: Databases]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has collected Salesforce datasets from victims in the airline and retail sectors.(Citation: ElecticIQ Buyukkaya_ShinyHunters_Sept2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0d35cd6-3fdb-476e-b830-214f32c2d104`.
