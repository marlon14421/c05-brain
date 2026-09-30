---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1025"
target_object: "T1112"
stix_relationship_id: "relationship--c2c31b26-7e42-43b6-964b-c959cabc53a4"
---
# Relationship 6951: S1025 — uses → T1112

**Source object:** [[01 ATT&CK/S1025 - Amadey|S1025: Amadey]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Amadey](https://attack.mitre.org/software/S1025) has overwritten registry keys for persistence.(Citation: BlackBerry Amadey 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2c31b26-7e42-43b6-964b-c959cabc53a4`.
