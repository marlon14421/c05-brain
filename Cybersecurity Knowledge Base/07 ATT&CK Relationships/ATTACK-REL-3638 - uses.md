---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0596"
target_object: "T1132.002"
stix_relationship_id: "relationship--951c72ac-3839-4716-a052-ffa79f5b62fe"
---
# Relationship 3638: S0596 — uses → T1132.002

**Source object:** [[01 ATT&CK/S0596 - ShadowPad|S0596: ShadowPad]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.002 - Non-Standard Encoding|T1132.002: Non-Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShadowPad](https://attack.mitre.org/software/S0596) has encoded data as readable Latin characters.(Citation: Securelist ShadowPad Aug 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--951c72ac-3839-4716-a052-ffa79f5b62fe`.
