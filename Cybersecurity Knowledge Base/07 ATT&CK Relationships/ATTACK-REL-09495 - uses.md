---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1203"
target_object: "T1095"
stix_relationship_id: "relationship--24a917f3-08c0-4ba1-955d-7e9c65dc26f7"
---
# Relationship 9495: S1203 — uses → T1095

**Source object:** [[01 ATT&CK/S1203 - J-magic|S1203: J-magic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[J-magic](https://attack.mitre.org/software/S1203) can monitor incoming C2 communications sent over TCP to the compromised host.(Citation: Lumen J-Magic JAN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--24a917f3-08c0-4ba1-955d-7e9c65dc26f7`.
