---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1571"
stix_relationship_id: "relationship--af74a9b1-6c74-45b6-a21d-38686afb202c"
---
# Relationship 7715: S1078 — uses → T1571

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RotaJakiro](https://attack.mitre.org/software/S1078) uses a custom binary protocol over TCP port 443.(Citation: netlab360 rotajakiro vs oceanlotus)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af74a9b1-6c74-45b6-a21d-38686afb202c`.
