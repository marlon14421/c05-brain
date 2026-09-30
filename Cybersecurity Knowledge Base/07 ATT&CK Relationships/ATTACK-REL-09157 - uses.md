---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9020"
target_object: "T1083"
stix_relationship_id: "relationship--ca5fef73-8710-4c03-a9ea-2012d6287cae"
---
# Relationship 9157: S9020 — uses → T1083

**Source object:** [[01 ATT&CK/S9020 - LODEINFO|S9020: LODEINFO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LODEINFO](https://attack.mitre.org/software/S9020) has the ability to designate specific files and folders to encryption.(Citation: ESET MirrorFace DEC 2022)(Citation: ITOCHU LODEINFO JAN 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca5fef73-8710-4c03-a9ea-2012d6287cae`.
