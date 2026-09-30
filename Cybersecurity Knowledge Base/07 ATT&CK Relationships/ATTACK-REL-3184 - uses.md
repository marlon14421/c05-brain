---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0574"
target_object: "T1106"
stix_relationship_id: "relationship--a33dbef1-994b-4dec-accb-6e63e9858f3e"
---
# Relationship 3184: S0574 — uses → T1106

**Source object:** [[01 ATT&CK/S0574 - BendyBear|S0574: BendyBear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BendyBear](https://attack.mitre.org/software/S0574) can load and execute modules and Windows Application Programming (API) calls using standard shellcode API hashing.(Citation: Unit42 BendyBear Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a33dbef1-994b-4dec-accb-6e63e9858f3e`.
