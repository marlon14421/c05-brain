---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0123"
target_object: "S0569"
stix_relationship_id: "relationship--72ff8ebb-a0fe-4ea0-9e4a-0f9aa2d48bc5"
---
# Relationship 9152: G0123 — uses → S0569

**Source object:** [[01 ATT&CK/G0123 - Volatile Cedar|G0123: Volatile Cedar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0569 - Explosive|S0569: Explosive]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: CheckPoint Volatile Cedar March 2015)(Citation: ClearSky Lebanese Cedar Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72ff8ebb-a0fe-4ea0-9e4a-0f9aa2d48bc5`.
