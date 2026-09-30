---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0674"
target_object: "T1112"
stix_relationship_id: "relationship--0167fba6-d37d-46ba-bb07-5fc70b864b3f"
---
# Relationship 5301: S0674 — uses → T1112

**Source object:** [[01 ATT&CK/S0674 - CharmPower|S0674: CharmPower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CharmPower](https://attack.mitre.org/software/S0674) can remove persistence-related artifacts from the Registry.(Citation: Check Point APT35 CharmPower January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0167fba6-d37d-46ba-bb07-5fc70b864b3f`.
