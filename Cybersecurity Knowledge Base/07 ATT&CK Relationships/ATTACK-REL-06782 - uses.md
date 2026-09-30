---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0239"
target_object: "T1571"
stix_relationship_id: "relationship--e9b71895-a9d2-4023-930b-4204f6c2d325"
---
# Relationship 6782: S0239 — uses → T1571

**Source object:** [[01 ATT&CK/S0239 - Bankshot|S0239: Bankshot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bankshot](https://attack.mitre.org/software/S0239) binds and listens on port 1058 for HTTP traffic while also utilizing a FakeTLS method.(Citation: US-CERT Bankshot Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9b71895-a9d2-4023-930b-4204f6c2d325`.
