---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0223"
target_object: "T1033"
stix_relationship_id: "relationship--1567eaca-2b2e-44df-b447-87769738e00a"
---
# Relationship 5295: S0223 — uses → T1033

**Source object:** [[01 ATT&CK/S0223 - POWERSTATS|S0223: POWERSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSTATS](https://attack.mitre.org/software/S0223) has the ability to identify the username on the compromised host.(Citation: TrendMicro POWERSTATS V3 June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1567eaca-2b2e-44df-b447-87769738e00a`.
