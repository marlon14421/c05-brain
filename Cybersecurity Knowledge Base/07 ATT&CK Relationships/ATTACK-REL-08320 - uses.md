---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "S1223"
stix_relationship_id: "relationship--2bad6d78-dfb0-4f6c-af0e-97f047187ae6"
---
# Relationship 8320: G1048 — uses → S1223

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1223 - THINCRUST|S1223: THINCRUST]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2bad6d78-dfb0-4f6c-af0e-97f047187ae6`.
