---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0691"
target_object: "T1033"
stix_relationship_id: "relationship--80a8ee57-3169-4928-aa94-56d356b72931"
---
# Relationship 5342: S0691 — uses → T1033

**Source object:** [[01 ATT&CK/S0691 - Neoichor|S0691: Neoichor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Neoichor](https://attack.mitre.org/software/S0691) can collect the user name from a victim's machine.(Citation: Microsoft NICKEL December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80a8ee57-3169-4928-aa94-56d356b72931`.
