---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0629"
target_object: "T1095"
stix_relationship_id: "relationship--b23da7b5-0d2d-4cfa-a2ad-ea89d86fecc6"
---
# Relationship 9335: S0629 — uses → T1095

**Source object:** [[01 ATT&CK/S0629 - RainyDay|S0629: RainyDay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RainyDay](https://attack.mitre.org/software/S0629) can use TCP in C2 communications.(Citation: Bitdefender Naikon April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b23da7b5-0d2d-4cfa-a2ad-ea89d86fecc6`.
