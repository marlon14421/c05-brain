---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0585"
target_object: "T1059.005"
stix_relationship_id: "relationship--08e172e1-561d-4bb9-a1a5-259131686547"
---
# Relationship 8915: S0585 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0585 - Kerrdown|S0585: Kerrdown]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kerrdown](https://attack.mitre.org/software/S0585) can use a VBS base64 decoder function published by Motobit.(Citation: Unit 42 KerrDown February 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08e172e1-561d-4bb9-a1a5-259131686547`.
