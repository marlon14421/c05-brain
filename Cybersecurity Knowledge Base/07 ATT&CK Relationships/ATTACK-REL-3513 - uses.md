---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0647"
target_object: "T1033"
stix_relationship_id: "relationship--4abb6550-b362-4f8a-80e4-1d6f094a1e37"
---
# Relationship 3513: S0647 — uses → T1033

**Source object:** [[01 ATT&CK/S0647 - Turian|S0647: Turian]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Turian](https://attack.mitre.org/software/S0647) can retrieve usernames.(Citation: ESET BackdoorDiplomacy Jun 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4abb6550-b362-4f8a-80e4-1d6f094a1e37`.
