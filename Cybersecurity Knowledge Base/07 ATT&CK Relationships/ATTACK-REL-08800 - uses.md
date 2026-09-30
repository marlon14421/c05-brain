---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1588.002"
stix_relationship_id: "relationship--612d9ccc-07ab-44fd-b970-869e9a730b02"
---
# Relationship 8800: G1041 — uses → T1588.002

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) has used tools such as Adminer during intrusions.(Citation: Hunt Sea Turtle 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--612d9ccc-07ab-44fd-b970-869e9a730b02`.
