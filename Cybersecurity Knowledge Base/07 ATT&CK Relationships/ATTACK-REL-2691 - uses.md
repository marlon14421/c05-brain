---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0511"
target_object: "T1112"
stix_relationship_id: "relationship--87630bba-4308-46f2-9601-7d30795a2eb6"
---
# Relationship 2691: S0511 — uses → T1112

**Source object:** [[01 ATT&CK/S0511 - RegDuke|S0511: RegDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RegDuke](https://attack.mitre.org/software/S0511) can create seemingly legitimate Registry key to store its encryption key.(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87630bba-4308-46f2-9601-7d30795a2eb6`.
