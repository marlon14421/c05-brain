---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1107"
target_object: "T1059.004"
stix_relationship_id: "relationship--0ab3c5b0-1536-4b65-9feb-48dd8a9981a1"
---
# Relationship 6388: S1107 — uses → T1059.004

**Source object:** [[01 ATT&CK/S1107 - NKAbuse|S1107: NKAbuse]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NKAbuse](https://attack.mitre.org/software/S1107) is initially installed and executed through an initial shell script.(Citation: NKAbuse SL)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ab3c5b0-1536-4b65-9feb-48dd8a9981a1`.
