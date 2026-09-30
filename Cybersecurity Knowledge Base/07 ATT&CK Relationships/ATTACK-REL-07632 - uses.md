---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0015"
target_object: "S0575"
stix_relationship_id: "relationship--68b29908-fcbc-464a-b9ed-63ef522bfe81"
---
# Relationship 7632: C0015 — uses → S0575

**Source object:** [[01 ATT&CK/C0015 - C0015|C0015: C0015]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0575 - Conti|S0575: Conti]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: DFIR Conti Bazar Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68b29908-fcbc-464a-b9ed-63ef522bfe81`.
