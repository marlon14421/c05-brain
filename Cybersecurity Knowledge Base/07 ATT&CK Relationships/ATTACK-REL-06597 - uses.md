---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0518"
target_object: "T1105"
stix_relationship_id: "relationship--28d3336f-108b-40fb-b3d7-9ec4311931c4"
---
# Relationship 6597: S0518 — uses → T1105

**Source object:** [[01 ATT&CK/S0518 - PolyglotDuke|S0518: PolyglotDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PolyglotDuke](https://attack.mitre.org/software/S0518) can retrieve payloads from the C2 server.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--28d3336f-108b-40fb-b3d7-9ec4311931c4`.
