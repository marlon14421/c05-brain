---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0052"
target_object: "T1560.001"
stix_relationship_id: "relationship--2e82ef21-9fb2-421e-bd96-73599089b448"
---
# Relationship 3674: G0052 — uses → T1560.001

**Source object:** [[01 ATT&CK/G0052 - CopyKittens|G0052: CopyKittens]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CopyKittens](https://attack.mitre.org/groups/G0052) uses ZPP, a .NET console program, to compress files with ZIP.(Citation: ClearSky Wilted Tulip July 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e82ef21-9fb2-421e-bd96-73599089b448`.
