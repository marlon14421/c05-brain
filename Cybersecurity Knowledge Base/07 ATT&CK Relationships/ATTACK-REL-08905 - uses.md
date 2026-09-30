---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0585"
target_object: "T1027.015"
stix_relationship_id: "relationship--b86ea4c6-4f1d-4f52-9191-28d3d4d610f7"
---
# Relationship 8905: S0585 — uses → T1027.015

**Source object:** [[01 ATT&CK/S0585 - Kerrdown|S0585: Kerrdown]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kerrdown](https://attack.mitre.org/software/S0585) can encrypt, encode, and compress multiple layers of shellcode.(Citation: Unit 42 KerrDown February 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b86ea4c6-4f1d-4f52-9191-28d3d4d610f7`.
