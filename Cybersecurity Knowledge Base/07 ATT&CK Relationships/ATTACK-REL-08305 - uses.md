---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0694"
target_object: "T1033"
stix_relationship_id: "relationship--022ba33a-16f4-40de-b0b2-4961870aa0c9"
---
# Relationship 8305: S0694 — uses → T1033

**Source object:** [[01 ATT&CK/S0694 - DRATzarus|S0694: DRATzarus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRATzarus](https://attack.mitre.org/software/S0694) can obtain a list of users from an infected machine.(Citation: ClearSky Lazarus Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--022ba33a-16f4-40de-b0b2-4961870aa0c9`.
