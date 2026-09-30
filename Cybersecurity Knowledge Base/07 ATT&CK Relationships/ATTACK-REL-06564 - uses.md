---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0699"
target_object: "T1132"
stix_relationship_id: "relationship--448cab31-deb1-40d5-a7f6-848d0116c4b6"
---
# Relationship 6564: S0699 — uses → T1132

**Source object:** [[01 ATT&CK/S0699 - Mythic|S0699: Mythic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132 - Data Encoding|T1132: Data Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mythic](https://attack.mitre.org/software/S0699) provides various transform functions to encode and/or randomize C2 data.(Citation: Mythc Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--448cab31-deb1-40d5-a7f6-848d0116c4b6`.
