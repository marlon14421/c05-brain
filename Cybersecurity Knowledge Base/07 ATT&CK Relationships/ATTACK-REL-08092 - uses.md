---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0053"
target_object: "T1560.002"
stix_relationship_id: "relationship--45522d60-160a-4c07-bd98-9a487175910e"
---
# Relationship 8092: S0053 — uses → T1560.002

**Source object:** [[01 ATT&CK/S0053 - SeaDuke|S0053: SeaDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.002 - Archive via Library|T1560.002: Archive via Library]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SeaDuke](https://attack.mitre.org/software/S0053) compressed data with zlib prior to sending it over C2.(Citation: Mandiant No Easy Breach)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45522d60-160a-4c07-bd98-9a487175910e`.
