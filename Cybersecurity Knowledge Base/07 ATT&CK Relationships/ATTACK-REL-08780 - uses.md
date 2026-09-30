---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1033"
target_object: "T1588.002"
stix_relationship_id: "relationship--c1340ca5-8aa5-442b-8715-b2c9a525d14f"
---
# Relationship 8780: G1033 — uses → T1588.002

**Source object:** [[01 ATT&CK/G1033 - Star Blizzard|G1033: Star Blizzard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Star Blizzard](https://attack.mitre.org/groups/G1033) has incorporated the open-source EvilGinx framework into their spearphishing activity.(Citation: CISA Star Blizzard Advisory December 2023)(Citation: StarBlizzard)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1340ca5-8aa5-442b-8715-b2c9a525d14f`.
