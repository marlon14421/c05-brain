---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1012"
stix_relationship_id: "relationship--79cebb53-3154-4512-9343-2942b1f72ff5"
---
# Relationship 9372: S0182 — uses → T1012

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FinFisher](https://attack.mitre.org/software/S0182) queries Registry values as part of its anti-sandbox checks.(Citation: FinFisher Citation)(Citation: Microsoft FinFisher March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79cebb53-3154-4512-9343-2942b1f72ff5`.
