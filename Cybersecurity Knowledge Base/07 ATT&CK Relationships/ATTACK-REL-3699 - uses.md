---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1226"
target_object: "T1112"
stix_relationship_id: "relationship--53d6538d-5b30-4503-94a3-077ddc428a3a"
---
# Relationship 3699: S1226 — uses → T1112

**Source object:** [[01 ATT&CK/S1226 - BOOKWORM|S1226: BOOKWORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BOOKWORM](https://attack.mitre.org/software/S1226) has modified Registry key values as part of its created service `DeviceSync`. (Citation: Unit42 Bookworm Nov2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--53d6538d-5b30-4503-94a3-077ddc428a3a`.
