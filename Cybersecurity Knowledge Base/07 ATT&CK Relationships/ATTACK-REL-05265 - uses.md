---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0513"
target_object: "T1071.001"
stix_relationship_id: "relationship--37539ea1-3b70-4e95-853f-e023d8bfc203"
---
# Relationship 5265: S0513 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0513 - LiteDuke|S0513: LiteDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LiteDuke](https://attack.mitre.org/software/S0513) can use HTTP GET requests in C2 communications.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37539ea1-3b70-4e95-853f-e023d8bfc203`.
