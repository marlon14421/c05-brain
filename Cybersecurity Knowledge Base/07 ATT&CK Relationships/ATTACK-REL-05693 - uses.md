---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0691"
target_object: "T1614.001"
stix_relationship_id: "relationship--746c2ff0-e5a1-494f-a9c9-bc45faceb5c5"
---
# Relationship 5693: S0691 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0691 - Neoichor|S0691: Neoichor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Neoichor](https://attack.mitre.org/software/S0691) can identify the system language on a compromised host.(Citation: Microsoft NICKEL December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--746c2ff0-e5a1-494f-a9c9-bc45faceb5c5`.
