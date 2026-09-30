---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1025"
target_object: "T1568.001"
stix_relationship_id: "relationship--1d91840d-b419-4d9f-9bba-8a9f18728854"
---
# Relationship 9806: S1025 — uses → T1568.001

**Source object:** [[01 ATT&CK/S1025 - Amadey|S1025: Amadey]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.001 - Fast Flux DNS|T1568.001: Fast Flux DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Amadey](https://attack.mitre.org/software/S1025) has used fast flux DNS for its C2.(Citation: Korean FSI TA505 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d91840d-b419-4d9f-9bba-8a9f18728854`.
