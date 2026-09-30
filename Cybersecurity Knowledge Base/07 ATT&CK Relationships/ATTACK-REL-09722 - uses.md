---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1229"
target_object: "T1083"
stix_relationship_id: "relationship--6b8ccd02-050f-40fa-8d03-36f1cc8f952b"
---
# Relationship 9722: S1229 — uses → T1083

**Source object:** [[01 ATT&CK/S1229 - Havoc|S1229: Havoc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Havoc](https://attack.mitre.org/software/S1229) interface can display a file explorer view of the compromised host.(Citation: Havoc Framework Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b8ccd02-050f-40fa-8d03-36f1cc8f952b`.
