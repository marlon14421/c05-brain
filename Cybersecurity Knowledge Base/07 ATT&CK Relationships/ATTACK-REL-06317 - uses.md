---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0410"
target_object: "T1083"
stix_relationship_id: "relationship--13b78b09-00b6-4307-87b7-7cd8c9360b39"
---
# Relationship 6317: S0410 — uses → T1083

**Source object:** [[01 ATT&CK/S0410 - Fysbis|S0410: Fysbis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Fysbis](https://attack.mitre.org/software/S0410) has the ability to search for files.(Citation: Fysbis Dr Web Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13b78b09-00b6-4307-87b7-7cd8c9360b39`.
